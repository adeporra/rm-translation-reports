# Real Madrid — AEM Translation Reports

Automated daily analysis of AEM Cloud Service PROD author `aemerror` logs for translation job performance monitoring.

## View reports

| Where | Link |
|-------|------|
| **Dashboard (browser)** | [adeporra.github.io/rm-translation-reports](https://adeporra.github.io/rm-translation-reports) |
| **Summary (GitHub)** | [reports/SUMMARY.md](reports/SUMMARY.md) |

## What it does

Every morning at 09:00 CET, a GitHub Actions workflow:

1. Authenticates to Adobe IMS using OAuth Server-to-Server credentials
2. Downloads the previous day's `aemerror` log from Cloud Manager API
3. Parses translation pipeline events, errors, retries, and RMTranslationRequest activity
4. Updates consolidated reports (CSV, HTML, XLSX, SUMMARY.md) with the new day's data
5. Commits the updated reports back to this repository
6. Deploys the reports to GitHub Pages for browser viewing

## Reports

| File | Description |
|------|-------------|
| `reports/SUMMARY.md` | Quick view — KPIs, per-day table, retry highlights (renders on GitHub) |
| `reports/translation_jobs_all_days.html` | Dashboard — dark-themed HTML with full styling (served via GitHub Pages) |
| `reports/translation_jobs_all_days.csv` | Raw data — all translation jobs with timestamps, durations, retry info |
| `reports/translation_jobs_all_days.xlsx` | Spreadsheet — multi-sheet workbook (Jobs, Summary, Errors, RMTranslationRequest) |
| `reports/metadata.json` | Internal — error counts and token summaries per date |

## Setup

### Prerequisites

1. **Adobe Developer Console** — OAuth Server-to-Server credential with the **Cloud Manager API** added
2. **Adobe Admin Console** — The credential's technical account must be assigned to a Cloud Manager product profile

#### Granting Cloud Manager API access

The credential currently returns `403025 Profile is not valid` when calling the Cloud Manager API. To fix:

1. Go to [Adobe Developer Console](https://developer.adobe.com/console/) → select the project containing your credential
2. Click **Add API** → select **Cloud Manager** → choose the OAuth Server-to-Server credential
3. Go to [Adobe Admin Console](https://adminconsole.adobe.com/) → **Products** → **Cloud Manager**
4. Select a product profile (e.g., **Developer** or **Deployment Manager**)
5. Click **API credentials** tab → add the credential's technical account email
6. Verify by running the workflow manually from the Actions tab

### Configure GitHub Secrets

Go to **Settings → Secrets and variables → Actions** and add:

| Secret | Value |
|--------|-------|
| `ADOBE_CLIENT_ID` | OAuth client ID from Adobe Developer Console |
| `ADOBE_CLIENT_SECRET` | OAuth client secret |

### Enable GitHub Pages

To view the HTML dashboard in a browser:

1. Go to **Settings → Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. **Branch**: select `gh-pages` and `/ (root)`
4. Save — the workflow deploys to `gh-pages` after each run
5. Your dashboard will be at `https://<username>.github.io/rm-translation-reports/`

### Manual Run

You can trigger the workflow manually from the **Actions** tab:

1. Go to **Actions → Daily Translation Report**
2. Click **Run workflow**
3. Optionally set `days_back` (default: 1 = yesterday, 2 = two days ago, etc.)

### Local Analysis

Run the analysis script directly on a local log file:

```bash
pip install -r scripts/requirements.txt
python scripts/analyze_translation_log.py /path/to/author_aemerror_2026-03-12.log --reports-dir reports/
```

## Environment

- **Program ID**: 47754
- **Environment ID**: 237306 (PROD Author)
- **IMS Org**: 114744A66135CF9B0A495FEB@AdobeOrg
- **AEM**: author-p47754-e237306.adobeaemcloud.com

## Tracked Metrics

- **Translation job lifecycle**: Created → ContentAddition → InProgress → ReadyForReview → Approved/Error
- **Phase durations**: Content gathering, translation (GPT-4o), review, approval
- **Retry detection**: Correlates API call errors with pipeline events to identify retried jobs
- **Error categorization**: Language copy, workflow errors, ResourceUtils, LockUtil, etc.
- **RMTranslationRequest**: Azure token operations, API errors, token size logging (DEBUG level)

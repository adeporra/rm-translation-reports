# Translation Jobs Report — PROD Author

*7 day(s): 2026-10-03, 2026-10-04, 2026-10-06, 2026-10-07, 2026-10-20, 2026-10-21, 2026-10-22*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 608 |
| **Approved** | 596 |
| **Errors** | 0 |
| **Stuck** | 7 |
| **Unknown** | 5 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 8.9s |
| **Min / Max** | 1.7s / 2m 19.8s |
| **API Requests** | 3,991 |
| **Total Tokens** | 8,624,761 |
| **Prompt / Completion** | 6,927,874 / 1,696,887 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-03 | 96 | 96 | 0 | 0 | 0 | 0 | 1,529,804 |
| 2026-10-04 | 73 | 72 | 0 | 0 | 1 | 0 | 1,070,800 |
| 2026-10-06 | 89 | 88 | 0 | 0 | 1 | 0 | 772,181 |
| 2026-10-07 | 66 | 62 | 0 | 4 | 0 | 1 | 901,958 |
| 2026-10-20 | 61 | 57 | 0 | 1 | 3 | 0 | 975,736 |
| 2026-10-21 | 151 | 151 | 0 | 0 | 0 | 0 | 2,502,397 |
| 2026-10-22 | 72 | 70 | 0 | 2 | 0 | 2 | 871,885 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-10-07 | 35 | `translationjob2207` | Nathalie Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-10-22 | 11 | `translationjob745` | Raquel Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-10-22 | 13 | `translationjob747` | Raquel Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 875,891 |
| ReplicationNewsAssemblyListener | 326,256 |
| TranslateHrefAttributes | 73,358 |
| Language copy not found | 66,154 |
| Error executing workflow | 32,540 |
| LockUtil contention | 17,323 |
| ResourceUtils commit | 7,827 |
| ThumbnailServlet | 6,487 |
| GCCScriptProcessor | 1,149 |
| TranslationCleanupJobConsumer | 1,109 |

*Generated 2026-10-23 11:05*

# Translation Jobs Report — PROD Author

*8 day(s): 2026-10-03, 2026-10-04, 2026-10-06, 2026-10-07, 2026-10-20, 2026-10-21, 2026-10-22, 2026-10-23*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 658 |
| **Approved** | 645 |
| **Errors** | 0 |
| **Stuck** | 7 |
| **Unknown** | 6 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 8.7s |
| **Min / Max** | 1.7s / 2m 19.8s |
| **API Requests** | 4,259 |
| **Total Tokens** | 9,116,217 |
| **Prompt / Completion** | 7,352,783 / 1,763,434 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-03 | 96 | 96 | 0 | 0 | 0 | 0 | 1,529,804 |
| 2026-10-04 | 73 | 72 | 0 | 0 | 1 | 0 | 1,070,800 |
| 2026-10-06 | 89 | 88 | 0 | 0 | 1 | 0 | 772,181 |
| 2026-10-07 | 66 | 62 | 0 | 4 | 0 | 1 | 901,958 |
| 2026-10-20 | 58 | 57 | 0 | 1 | 0 | 0 | 954,619 |
| 2026-10-21 | 151 | 151 | 0 | 0 | 0 | 0 | 2,502,397 |
| 2026-10-22 | 72 | 70 | 0 | 2 | 0 | 2 | 871,885 |
| 2026-10-23 | 53 | 49 | 0 | 0 | 4 | 0 | 512,573 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-10-07 | 35 | `translationjob2207` | Nathalie Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-10-22 | 11 | `translationjob745` | Raquel Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-10-22 | 13 | `translationjob747` | Raquel Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 977,552 |
| ReplicationNewsAssemblyListener | 356,893 |
| TranslateHrefAttributes | 76,643 |
| Language copy not found | 73,139 |
| Error executing workflow | 39,705 |
| LockUtil contention | 18,591 |
| ResourceUtils commit | 7,837 |
| ThumbnailServlet | 7,285 |
| TranslationCleanupJobConsumer | 1,339 |
| GCCScriptProcessor | 1,316 |

*Generated 2026-10-24 10:22*

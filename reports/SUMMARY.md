# Translation Jobs Report — PROD Author

*6 day(s): 2026-03-04, 2026-03-05, 2026-03-06, 2026-03-11, 2026-03-12, 2026-03-13*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 436 |
| **Approved** | 407 |
| **Errors** | 0 |
| **Stuck** | 9 |
| **Unknown** | 20 |
| **Retried & Recovered** | 7 |
| **Avg Duration** | 10.6s |
| **Min / Max** | 0.1s / 2m 27.3s |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried |
|------|------|---------|--------|-------|--------|---------|
| 2026-03-04 | 34 | 30 | 0 | 1 | 3 | 0 |
| 2026-03-05 | 61 | 57 | 0 | 0 | 4 | 0 |
| 2026-03-06 | 98 | 89 | 0 | 3 | 6 | 0 |
| 2026-03-11 | 110 | 106 | 0 | 1 | 3 | 1 |
| 2026-03-12 | 92 | 84 | 0 | 4 | 4 | 6 |
| 2026-03-13 | 41 | 41 | 0 | 0 | 0 | 0 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-03-11 | 47 | `translationjob54` | Ignacio -  Ai Translation Project | JA-JP | API call failed (payload dumped) → retried → APPROVED | APPROVED |
| 2026-03-12 | 28 | `translationjob12` | Alejandro Ai Translation Project | PT-PT | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-12 | 30 | `translationjob14` | Alejandro Ai Translation Project | AR-AE | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-12 | 31 | `translationjob15` | Alejandro Ai Translation Project | FR-FR | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-12 | 32 | `translationjob16` | Alejandro Ai Translation Project | JA-JP | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-12 | 46 | `translationjob24` | Alejandro Ai Translation Project | JA-JP | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-12 | 48 | `translationjob26` | Alejandro Ai Translation Project | JA-JP | API call failed (token_request_error) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 90,174 |
| ReplicationNewsAssemblyListener | 22,559 |
| ResourceUtils commit | 7,546 |
| LockUtil contention | 1,116 |
| TranslateHrefAttributes | 754 |
| Language copy not found | 727 |
| TranslationCleanupJobConsumer | 566 |
| ThumbnailServlet | 72 |
| GCCScriptProcessor | 40 |
| TicketAssemblyTranslationServiceImpl | 13 |

*Generated 2026-03-14 18:22*

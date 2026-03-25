# Translation Jobs Report — PROD Author

*4 day(s): 2026-03-21, 2026-03-22, 2026-03-23, 2026-03-24*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 334 |
| **Approved** | 309 |
| **Errors** | 0 |
| **Stuck** | 12 |
| **Unknown** | 13 |
| **Retried & Recovered** | 9 |
| **Avg Duration** | 11.1s |
| **Min / Max** | 1.7s / 1m 45.3s |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried |
|------|------|---------|--------|-------|--------|---------|
| 2026-03-21 | 54 | 53 | 0 | 1 | 0 | 0 |
| 2026-03-22 | 137 | 126 | 0 | 2 | 9 | 0 |
| 2026-03-23 | 78 | 71 | 0 | 3 | 4 | 3 |
| 2026-03-24 | 65 | 59 | 0 | 6 | 0 | 6 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-03-23 | 25 | `translationjob1` | Maria Ai Translation Project | PT-PT | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-23 | 26 | `translationjob4` | Maria Ai Translation Project | AR-AE | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-23 | 58 | `translationjob31` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-24 | 9 | `translationjob55` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 13 | `translationjob59` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 14 | `translationjob60` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 15 | `translationjob61` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 31 | `translationjob14` | Maria Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 55 | `translationjob243` | Alejandro Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| Language copy not found | 619,107 |
| ReplicationSquadListener | 396,996 |
| ReplicationNewsAssemblyListener | 172,983 |
| ResourceUtils commit | 64,235 |
| TranslateHrefAttributes | 6,986 |
| LockUtil contention | 6,466 |
| Error executing workflow | 2,864 |
| TranslationCleanupJobConsumer | 809 |
| ThumbnailServlet | 544 |
| Content LC unknown state | 347 |

*Generated 2026-03-25 05:25*

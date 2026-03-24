# Translation Jobs Report — PROD Author

*3 day(s): 2026-03-21, 2026-03-22, 2026-03-23*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 269 |
| **Approved** | 250 |
| **Errors** | 0 |
| **Stuck** | 6 |
| **Unknown** | 13 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 9.6s |
| **Min / Max** | 1.7s / 1m 45.3s |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried |
|------|------|---------|--------|-------|--------|---------|
| 2026-03-21 | 54 | 53 | 0 | 1 | 0 | 0 |
| 2026-03-22 | 137 | 126 | 0 | 2 | 9 | 0 |
| 2026-03-23 | 78 | 71 | 0 | 3 | 4 | 3 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-03-23 | 25 | `translationjob1` | Maria Ai Translation Project | PT-PT | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-23 | 26 | `translationjob4` | Maria Ai Translation Project | AR-AE | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-23 | 58 | `translationjob31` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| Language copy not found | 492,338 |
| ReplicationSquadListener | 306,128 |
| ReplicationNewsAssemblyListener | 158,742 |
| ResourceUtils commit | 51,090 |
| LockUtil contention | 4,977 |
| TranslateHrefAttributes | 4,848 |
| Error executing workflow | 2,444 |
| TranslationCleanupJobConsumer | 801 |
| ThumbnailServlet | 372 |
| Content LC unknown state | 258 |

*Generated 2026-03-24 05:25*

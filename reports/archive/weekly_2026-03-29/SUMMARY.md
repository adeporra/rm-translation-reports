# Translation Jobs Report — PROD Author

*7 day(s): 2026-03-21, 2026-03-22, 2026-03-23, 2026-03-24, 2026-03-25, 2026-03-26, 2026-03-27*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 574 |
| **Approved** | 533 |
| **Errors** | 0 |
| **Stuck** | 29 |
| **Unknown** | 12 |
| **Retried & Recovered** | 14 |
| **Avg Duration** | 11.2s |
| **Min / Max** | 2.0s / 1m 56.2s |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried |
|------|------|---------|--------|-------|--------|---------|
| 2026-03-21 | 49 | 48 | 0 | 1 | 0 | 0 |
| 2026-03-22 | 137 | 126 | 0 | 2 | 9 | 0 |
| 2026-03-23 | 67 | 62 | 0 | 3 | 2 | 2 |
| 2026-03-24 | 60 | 54 | 0 | 6 | 0 | 6 |
| 2026-03-25 | 81 | 68 | 0 | 13 | 0 | 6 |
| 2026-03-26 | 97 | 97 | 0 | 0 | 0 | 0 |
| 2026-03-27 | 83 | 78 | 0 | 4 | 1 | 0 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-03-23 | 25 | `translationjob4` | Maria Ai Translation Project | AR-AE | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-23 | 50 | `translationjob31` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-24 | 9 | `translationjob55` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 13 | `translationjob59` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 14 | `translationjob60` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 15 | `translationjob61` | Nathalie Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 29 | `translationjob14` | Maria Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-24 | 50 | `translationjob243` | Alejandro Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 15 | `translationjob22` | Maria Ai Translation Project | EN-US | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 17 | `translationjob26` | Maria Ai Translation Project | JA-JP | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 19 | `translationjob28` | Maria Ai Translation Project | PT-PT | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 21 | `translationjob31` | Maria Ai Translation Project | AR-AE | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 22 | `translationjob32` | Maria Ai Translation Project | AR-AE | API call failed (token_request_error) | IN_PROGRESS |
| 2026-03-25 | 24 | `translationjob35` | Maria Ai Translation Project | JA-JP | API call failed (token_request_error) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| Language copy not found | 816,035 |
| ReplicationSquadListener | 812,590 |
| ReplicationNewsAssemblyListener | 344,456 |
| ResourceUtils commit | 111,015 |
| LockUtil contention | 12,085 |
| TranslateHrefAttributes | 10,750 |
| Error executing workflow | 3,867 |
| TranslationCleanupJobConsumer | 2,109 |
| ThumbnailServlet | 1,332 |
| Content LC unknown state | 933 |

*Generated 2026-03-28 05:22*

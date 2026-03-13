# Translation Jobs Report — PROD Author

*5 day(s): 2026-03-04, 2026-03-05, 2026-03-06, 2026-03-11, 2026-03-12*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 374 |
| **Approved** | 344 |
| **Errors** | 0 |
| **Stuck** | 8 |
| **Unknown** | 22 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 12.5s |
| **Min / Max** | 0.1s / 2m 27.3s |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried |
|------|------|---------|--------|-------|--------|---------|
| 2026-03-04 | 34 | 30 | 0 | 1 | 3 | 0 |
| 2026-03-05 | 61 | 57 | 0 | 0 | 4 | 0 |
| 2026-03-06 | 98 | 89 | 0 | 3 | 6 | 0 |
| 2026-03-11 | 110 | 106 | 0 | 1 | 3 | 1 |
| 2026-03-12 | 71 | 62 | 0 | 3 | 6 | 2 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-03-11 | 47 | `translationjob54` | Ignacio -  Ai Translation Project | JA-JP | API call failed (payload dumped) → retried → APPROVED | APPROVED |
| 2026-03-12 | 5 | `translationjob102` | Ignacio Ai Translation Project | JA-JP | API call failed (token_request_error) → retried → APPROVED | APPROVED |
| 2026-03-12 | 11 | `translationjob108` | Ignacio Ai Translation Project | JA-JP | API call failed (token_request_error) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| Language copy not found | 156,920 |
| ReplicationSquadListener | 71,216 |
| ResourceUtils commit | 6,164 |
| LockUtil contention | 781 |
| TranslateHrefAttributes | 684 |
| ThumbnailServlet | 307 |
| Error executing workflow | 205 |
| Content LC unknown state | 169 |
| ReplicationNewsAssemblyListener | 149 |
| TicketAssemblyTranslationServiceImpl | 15 |

*Generated 2026-03-13 17:56*

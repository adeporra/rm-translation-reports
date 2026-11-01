# Translation Jobs Report — PROD Author

*7 day(s): 2026-10-24, 2026-10-25, 2026-10-26, 2026-10-27, 2026-10-28, 2026-10-29, 2026-10-30*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 513 |
| **Approved** | 502 |
| **Errors** | 0 |
| **Stuck** | 5 |
| **Unknown** | 6 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 9.6s |
| **Min / Max** | 2.0s / 2m 37.6s |
| **API Requests** | 3,264 |
| **Total Tokens** | 7,200,566 |
| **Prompt / Completion** | 5,742,279 / 1,458,287 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-24 | 36 | 33 | 0 | 2 | 1 | 0 | 185,408 |
| 2026-10-25 | 110 | 109 | 0 | 0 | 1 | 0 | 1,929,926 |
| 2026-10-26 | 59 | 59 | 0 | 0 | 0 | 0 | 709,192 |
| 2026-10-27 | 90 | 89 | 0 | 1 | 0 | 1 | 1,327,093 |
| 2026-10-28 | 75 | 73 | 0 | 1 | 1 | 1 | 1,132,523 |
| 2026-10-29 | 52 | 51 | 0 | 1 | 0 | 0 | 660,660 |
| 2026-10-30 | 91 | 88 | 0 | 0 | 3 | 1 | 1,255,764 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-10-27 | 15 | `translationjob2662` | Ignacio Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-10-28 | 1 | `translationjob841` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-10-30 | 4 | `translationjob2156` | Maria Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 921,852 |
| ReplicationNewsAssemblyListener | 436,028 |
| Language copy not found | 192,686 |
| TranslateHrefAttributes | 33,999 |
| Error executing workflow | 11,884 |
| LockUtil contention | 10,291 |
| ThumbnailServlet | 9,826 |
| ResourceUtils commit | 2,630 |
| TranslationCleanupJobConsumer | 1,282 |
| GCCScriptProcessor | 1,278 |

*Generated 2026-10-31 11:45*

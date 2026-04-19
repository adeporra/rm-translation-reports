# Translation Jobs Report — PROD Author

*6 day(s): 2026-04-11, 2026-04-12, 2026-04-13, 2026-04-14, 2026-04-15, 2026-04-16*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 552 |
| **Approved** | 540 |
| **Errors** | 0 |
| **Stuck** | 10 |
| **Unknown** | 2 |
| **Retried & Recovered** | 5 |
| **Avg Duration** | 13.3s |
| **Min / Max** | 1.7s / 3m 23.6s |
| **API Requests** | 1,736 |
| **Total Tokens** | 3,991,829 |
| **Prompt / Completion** | 3,129,105 / 862,724 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-04-11 | 47 | 47 | 0 | 0 | 0 | 0 | — |
| 2026-04-12 | 81 | 77 | 0 | 4 | 0 | 0 | — |
| 2026-04-13 | 46 | 46 | 0 | 0 | 0 | 0 | — |
| 2026-04-14 | 70 | 70 | 0 | 0 | 0 | 2 | — |
| 2026-04-15 | 164 | 163 | 0 | 1 | 0 | 2 | 1,747,893 |
| 2026-04-16 | 144 | 137 | 0 | 5 | 2 | 1 | 2,243,936 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-04-14 | 26 | `translationjob12` | Nathalie Ai Translation Project | PT-PT | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-04-14 | 30 | `translationjob16` | Nathalie Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-04-15 | 58 | `translationjob47` | Ignacio Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-04-15 | 159 | `translationjob126` | Maria Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-04-16 | 18 | `translationjob141` | Maria Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| Language copy not found | 1,260,861 |
| ReplicationSquadListener | 908,387 |
| ReplicationNewsAssemblyListener | 418,800 |
| ResourceUtils commit | 120,792 |
| TranslateHrefAttributes | 13,074 |
| LockUtil contention | 9,895 |
| Error executing workflow | 5,462 |
| ThumbnailServlet | 1,040 |
| TranslationCleanupJobConsumer | 702 |
| Content LC unknown state | 356 |

*Generated 2026-04-17 09:52*

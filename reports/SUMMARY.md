# Translation Jobs Report — PROD Author

*6 day(s): 2026-11-14, 2026-11-15, 2026-11-16, 2026-11-17, 2026-11-18, 2026-11-19*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 418 |
| **Approved** | 411 |
| **Errors** | 0 |
| **Stuck** | 4 |
| **Unknown** | 3 |
| **Retried & Recovered** | 6 |
| **Avg Duration** | 9.2s |
| **Min / Max** | 2.0s / 1m 5.5s |
| **API Requests** | 2,623 |
| **Total Tokens** | 5,680,592 |
| **Prompt / Completion** | 4,563,125 / 1,117,467 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-11-14 | 35 | 35 | 0 | 0 | 0 | 0 | 659,065 |
| 2026-11-15 | 23 | 21 | 0 | 0 | 2 | 0 | 134,163 |
| 2026-11-16 | 61 | 57 | 0 | 4 | 0 | 4 | 722,725 |
| 2026-11-17 | 116 | 116 | 0 | 0 | 0 | 2 | 1,762,075 |
| 2026-11-18 | 135 | 135 | 0 | 0 | 0 | 0 | 1,794,748 |
| 2026-11-19 | 48 | 47 | 0 | 0 | 1 | 0 | 607,816 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-11-16 | 8 | `translationjob963` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-16 | 9 | `translationjob964` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-16 | 13 | `translationjob968` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-16 | 14 | `translationjob1781` | Alejandro Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-17 | 3 | `translationjob805` | Raquel Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-17 | 21 | `translationjob2621` | Nathalie Ai Translation Project | DE-DE | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 963,023 |
| ReplicationNewsAssemblyListener | 602,482 |
| Language copy not found | 246,628 |
| TranslateHrefAttributes | 73,644 |
| LockUtil contention | 22,853 |
| ResourceUtils commit | 9,828 |
| ThumbnailServlet | 6,535 |
| Error executing workflow | 5,249 |
| TicketAssemblyTranslationServiceImpl | 1,280 |
| GCCScriptProcessor | 1,198 |

*Generated 2026-11-20 14:57*

# Translation Jobs Report — PROD Author

*3 day(s): 2026-11-21, 2026-11-22, 2026-11-23*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 311 |
| **Approved** | 302 |
| **Errors** | 0 |
| **Stuck** | 8 |
| **Unknown** | 1 |
| **Retried & Recovered** | 10 |
| **Avg Duration** | 9.6s |
| **Min / Max** | 1.6s / 1m 21.0s |
| **API Requests** | 2,375 |
| **Total Tokens** | 5,633,830 |
| **Prompt / Completion** | 4,357,464 / 1,276,366 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-11-21 | 124 | 124 | 0 | 0 | 0 | 0 | 2,738,435 |
| 2026-11-22 | 72 | 72 | 0 | 0 | 0 | 0 | 1,348,626 |
| 2026-11-23 | 115 | 106 | 0 | 8 | 1 | 10 | 1,546,769 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-11-23 | 66 | `translationjob3135` | Ignacio Ai Translation Project | DE-DE | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-23 | 68 | `translationjob3137` | Ignacio Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 72 | `translationjob3141` | Ignacio Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 74 | `translationjob3143` | Ignacio Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 77 | `translationjob3146` | Ignacio Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-23 | 78 | `translationjob3147` | Ignacio Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 79 | `translationjob3148` | Ignacio Ai Translation Project | AR-AE | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 80 | `translationjob1018` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 81 | `translationjob1019` | Ana Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-23 | 94 | `translationjob1020` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 505,144 |
| ReplicationNewsAssemblyListener | 464,763 |
| Language copy not found | 192,963 |
| TranslateHrefAttributes | 20,216 |
| ResourceUtils commit | 12,582 |
| LockUtil contention | 6,320 |
| Error executing workflow | 6,174 |
| ThumbnailServlet | 3,028 |
| TicketAssemblyTranslationServiceImpl | 976 |
| GCCScriptProcessor | 599 |

*Generated 2026-11-24 17:01*

# Translation Jobs Report — PROD Author

*5 day(s): 2026-10-31, 2026-11-01, 2026-11-02, 2026-11-03, 2026-11-04*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 533 |
| **Approved** | 524 |
| **Errors** | 0 |
| **Stuck** | 5 |
| **Unknown** | 4 |
| **Retried & Recovered** | 4 |
| **Avg Duration** | 13.5s |
| **Min / Max** | 2.1s / 20m 53.6s |
| **API Requests** | 4,177 |
| **Total Tokens** | 8,897,760 |
| **Prompt / Completion** | 7,189,899 / 1,707,861 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-31 | 84 | 83 | 0 | 1 | 0 | 0 | 1,550,388 |
| 2026-11-01 | 132 | 132 | 0 | 0 | 0 | 0 | 2,449,860 |
| 2026-11-02 | 42 | 42 | 0 | 0 | 0 | 0 | 472,011 |
| 2026-11-03 | 108 | 108 | 0 | 0 | 0 | 1 | 1,736,484 |
| 2026-11-04 | 167 | 159 | 0 | 4 | 4 | 3 | 2,689,017 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-11-03 | 87 | `translationjob1652` | Alejandro Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-04 | 36 | `translationjob2491` | Nathalie Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-04 | 40 | `translationjob2492` | Nathalie Ai Translation Project | AR-AE | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-04 | 107 | `translationjob1691` | Gonzalo Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 704,895 |
| ReplicationNewsAssemblyListener | 607,018 |
| Language copy not found | 139,825 |
| TranslateHrefAttributes | 36,108 |
| LockUtil contention | 12,204 |
| ThumbnailServlet | 4,597 |
| ResourceUtils commit | 4,214 |
| Error executing workflow | 3,179 |
| GCCScriptProcessor | 1,166 |
| TicketAssemblyTranslationServiceImpl | 1,009 |

*Generated 2026-11-05 14:04*

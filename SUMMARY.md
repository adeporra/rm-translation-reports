# Translation Jobs Report — PROD Author

*7 day(s): 2026-10-31, 2026-11-01, 2026-11-02, 2026-11-03, 2026-11-04, 2026-11-05, 2026-11-06*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 638 |
| **Approved** | 628 |
| **Errors** | 0 |
| **Stuck** | 6 |
| **Unknown** | 4 |
| **Retried & Recovered** | 5 |
| **Avg Duration** | 12.8s |
| **Min / Max** | 2.1s / 20m 53.6s |
| **API Requests** | 4,884 |
| **Total Tokens** | 10,437,961 |
| **Prompt / Completion** | 8,424,591 / 2,013,370 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-31 | 84 | 83 | 0 | 1 | 0 | 0 | 1,550,388 |
| 2026-11-01 | 132 | 132 | 0 | 0 | 0 | 0 | 2,449,860 |
| 2026-11-02 | 42 | 42 | 0 | 0 | 0 | 0 | 472,011 |
| 2026-11-03 | 108 | 108 | 0 | 0 | 0 | 1 | 1,736,484 |
| 2026-11-04 | 165 | 159 | 0 | 4 | 2 | 3 | 2,664,441 |
| 2026-11-05 | 51 | 51 | 0 | 0 | 0 | 0 | 724,816 |
| 2026-11-06 | 56 | 53 | 0 | 1 | 2 | 1 | 839,961 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-11-03 | 87 | `translationjob1652` | Alejandro Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-04 | 36 | `translationjob2491` | Nathalie Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-04 | 40 | `translationjob2492` | Nathalie Ai Translation Project | AR-AE | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-04 | 107 | `translationjob1691` | Gonzalo Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-06 | 17 | `translationjob923` | Ana Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 984,285 |
| ReplicationNewsAssemblyListener | 680,483 |
| Language copy not found | 180,219 |
| TranslateHrefAttributes | 48,308 |
| LockUtil contention | 16,753 |
| ThumbnailServlet | 6,553 |
| ResourceUtils commit | 5,510 |
| Error executing workflow | 3,839 |
| GCCScriptProcessor | 1,515 |
| TranslationCleanupJobConsumer | 1,438 |

*Generated 2026-11-07 12:32*

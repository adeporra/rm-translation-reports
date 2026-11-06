# Translation Jobs Report — PROD Author

*6 day(s): 2026-10-31, 2026-11-01, 2026-11-02, 2026-11-03, 2026-11-04, 2026-11-05*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 584 |
| **Approved** | 575 |
| **Errors** | 0 |
| **Stuck** | 5 |
| **Unknown** | 4 |
| **Retried & Recovered** | 4 |
| **Avg Duration** | 13.1s |
| **Min / Max** | 2.1s / 20m 53.6s |
| **API Requests** | 4,570 |
| **Total Tokens** | 9,622,562 |
| **Prompt / Completion** | 7,814,644 / 1,807,918 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-10-31 | 84 | 83 | 0 | 1 | 0 | 0 | 1,550,388 |
| 2026-11-01 | 132 | 132 | 0 | 0 | 0 | 0 | 2,449,860 |
| 2026-11-02 | 42 | 42 | 0 | 0 | 0 | 0 | 472,011 |
| 2026-11-03 | 108 | 108 | 0 | 0 | 0 | 1 | 1,736,484 |
| 2026-11-04 | 165 | 159 | 0 | 4 | 2 | 3 | 2,664,441 |
| 2026-11-05 | 53 | 51 | 0 | 0 | 2 | 0 | 749,378 |

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
| ReplicationSquadListener | 851,189 |
| ReplicationNewsAssemblyListener | 657,897 |
| Language copy not found | 179,495 |
| TranslateHrefAttributes | 44,217 |
| LockUtil contention | 15,403 |
| ThumbnailServlet | 5,661 |
| ResourceUtils commit | 5,498 |
| Error executing workflow | 3,438 |
| GCCScriptProcessor | 1,355 |
| TranslationCleanupJobConsumer | 1,186 |

*Generated 2026-11-06 13:48*

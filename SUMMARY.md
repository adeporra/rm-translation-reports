# Translation Jobs Report — PROD Author

*6 day(s): 2026-11-07, 2026-11-08, 2026-11-09, 2026-11-10, 2026-11-11, 2026-11-12*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 307 |
| **Approved** | 302 |
| **Errors** | 0 |
| **Stuck** | 1 |
| **Unknown** | 4 |
| **Retried & Recovered** | 3 |
| **Avg Duration** | 12.1s |
| **Min / Max** | 2.2s / 3m 9.6s |
| **API Requests** | 1,895 |
| **Total Tokens** | 4,060,922 |
| **Prompt / Completion** | 3,278,023 / 782,899 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-11-07 | 21 | 21 | 0 | 0 | 0 | 0 | 66,596 |
| 2026-11-08 | 56 | 56 | 0 | 0 | 0 | 0 | 1,062,612 |
| 2026-11-09 | 49 | 49 | 0 | 0 | 0 | 0 | 672,428 |
| 2026-11-10 | 77 | 76 | 0 | 0 | 1 | 0 | 1,076,378 |
| 2026-11-11 | 53 | 51 | 0 | 1 | 1 | 2 | 534,722 |
| 2026-11-12 | 51 | 49 | 0 | 0 | 2 | 1 | 648,186 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-11-11 | 11 | `translationjob2579` | Nathalie Ai Translation Project | EN-US | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-11-11 | 35 | `translationjob2587` | Nathalie Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-11-12 | 18 | `translationjob2842` | Ignacio Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 894,335 |
| ReplicationNewsAssemblyListener | 512,189 |
| Language copy not found | 240,212 |
| TranslateHrefAttributes | 61,405 |
| LockUtil contention | 22,573 |
| ThumbnailServlet | 5,295 |
| ResourceUtils commit | 5,260 |
| Error executing workflow | 4,706 |
| TranslationCleanupJobConsumer | 1,158 |
| GCCScriptProcessor | 1,151 |

*Generated 2026-11-13 13:59*

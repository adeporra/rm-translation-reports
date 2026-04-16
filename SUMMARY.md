# Translation Jobs Report — PROD Author

*5 day(s): 2026-04-11, 2026-04-12, 2026-04-13, 2026-04-14, 2026-04-15*

[**View full dashboard →**](https://adeporra.github.io/rm-translation-reports/)

## Summary

| Metric | Value |
|--------|-------|
| **Total Jobs** | 408 |
| **Approved** | 403 |
| **Errors** | 0 |
| **Stuck** | 5 |
| **Unknown** | 0 |
| **Retried & Recovered** | 4 |
| **Avg Duration** | 10.7s |
| **Min / Max** | 1.7s / 1m 28.9s |
| **API Requests** | 649 |
| **Total Tokens** | 1,747,893 |
| **Prompt / Completion** | 1,296,272 / 451,621 |

## Per-day breakdown

| Date | Jobs | Approved | Errors | Stuck | Unknown | Retried | Total Tokens |
|------|------|---------|--------|-------|--------|---------|-------------|
| 2026-04-11 | 47 | 47 | 0 | 0 | 0 | 0 | — |
| 2026-04-12 | 81 | 77 | 0 | 4 | 0 | 0 | — |
| 2026-04-13 | 46 | 46 | 0 | 0 | 0 | 0 | — |
| 2026-04-14 | 70 | 70 | 0 | 0 | 0 | 2 | — |
| 2026-04-15 | 164 | 163 | 0 | 1 | 0 | 2 | 1,747,893 |

## Retry detection

| Date | # | Job ID | Project | Language | Detail | Status |
|------|---|--------|---------|----------|--------|--------|
| 2026-04-14 | 26 | `translationjob12` | Nathalie Ai Translation Project | PT-PT | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-04-14 | 30 | `translationjob16` | Nathalie Ai Translation Project | JA-JP | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |
| 2026-04-15 | 58 | `translationjob47` | Ignacio Ai Translation Project | JA-JP | API call failed (api_payload_dump) | IN_PROGRESS |
| 2026-04-15 | 159 | `translationjob126` | Maria Ai Translation Project | EN-US | API call failed (api_payload_dump) → retried → APPROVED | APPROVED |

## Top error categories

| Category | Total |
|----------|-------|
| ReplicationSquadListener | 758,943 |
| Language copy not found | 656,859 |
| ReplicationNewsAssemblyListener | 295,771 |
| ResourceUtils commit | 83,205 |
| TranslateHrefAttributes | 9,204 |
| LockUtil contention | 8,217 |
| Error executing workflow | 2,653 |
| ThumbnailServlet | 843 |
| TranslationCleanupJobConsumer | 689 |
| Content LC unknown state | 178 |

*Generated 2026-04-16 06:04*

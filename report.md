# Stellar Ecosystem Data Report

> Auto-generated on 2026-04-21

## Summary

| Metric | Count |
|--------|------:|
| Total projects | **671** |
| SCF-funded projects | 577 |
| Community projects | 94 |
| Audited projects | 48 |

## Data Coverage

| Field | Count | Coverage |
|-------|------:|---------:|
| description | 665/671 | 99.1% |
| website | 663/671 | 98.8% |
| blog | 242/671 | 36.1% |
| x | 483/671 | 72% |
| linkedin | 374/671 | 55.7% |
| discord | 204/671 | 30.4% |
| telegram | 142/671 | 21.2% |
| youtube | 161/671 | 24% |
| instagram | 110/671 | 16.4% |
| reddit | 11/671 | 1.6% |
| tiktok | 26/671 | 3.9% |
| linktree | 3/671 | 0.4% |
| github | 495/671 | 73.8% |
| category | 583/671 | 86.9% |
| tags | 666/671 | 99.3% |
| operating_region | 664/671 | 99% |
| based_in | 575/671 | 85.7% |

## Enrichment vs SCF Airtable

Per-project comparison of our **671** projects (incl. **94** community projects not in SCF) against **580** in SCF Airtable:

| Field | We Added | We Modified |
|-------|------:|------:|
| description | +117 | 548 |
| website | +133 | 530 |
| github | +113 | 382 |
| x | +199 | 284 |
| linkedin | +170 | 204 |
| discord | +95 | 109 |
| based_in | +99 | 476 |
| blog | +242 | 0 |
| telegram | +142 | 0 |
| youtube | +161 | 0 |
| instagram | +110 | 0 |
| reddit | +11 | 0 |
| tiktok | +26 | 0 |
| linktree | +3 | 0 |

*"Added" = we filled a field SCF didn't have. "Modified" = SCF had a value, we store a different one.*

## SCF Project Coverage

Of **577** SCF-funded projects:

| Field | Count | Coverage |
|-------|------:|---------:|
| awarded_total | 522/577 | 90.5% |
| awarded_round | 553/577 | 95.8% |
| submission_urls | 553/577 | 95.8% |
| website | 569/577 | 98.6% |
| github | 445/577 | 77.1% |

*Gaps are mostly early-round projects (SCF #1-4) that predate the submissions tracking system, so per-submission budget and round data is unavailable.*

## Ecosystem Activity

*Based on last GitHub push and last tweet from tracked accounts.*

| Period | GitHub | Twitter |
|--------|------:|--------:|
| Tracked projects | 448 | 446 |
| Active last week | 115 | 199 |
| Active last month | 176 | 252 |
| Active last 3 months | 233 | 296 |
| Active last year | 310 | 362 |

## Audit Data

**48** projects audited with **67** reports.

*Audit data provided by [Soroban Security](https://sorobansecurity.com).*

| Auditor | Reports |
|---------|---------:|
| Veridise | 22 |
| certora | 10 |
| OtterSec | 10 |
| Runtime Verification | 8 |
| Quarkslab | 6 |
| Halborn | 4 |
| CoinFabrik | 2 |
| OpenZeppelin | 2 |
| Cantina | 1 |
| Code4rena | 1 |
| Сoinspect | 1 |

## Data Sources

- **projects**: Stellar Community Fund (SCF) Airtable + community contributions
- **scf_submissions**: SCF submission records via communityfund.stellar.org
- **github**: GitHub API — repository stats, commit activity, contributors
- **twitter**: X/Twitter — account metadata, posting activity
- **audits**: Soroban Security (sorobansecurity.com) — smart contract audit reports

## Source Breakdown

Field-level provenance tracking:

| Source | Fields |
|--------|------:|
| submissions | 564 |
| airtable | 3719 |
| crawler | 723 |
| website | 1623 |
| agent:content-linker:approved | 2 |
| schedule | 1 |
| agent:project-enricher | 7 |
| soroban_security | 67 |

## Needs Review

14 items need attention.

**description empty** (6):
- nethermind
- alchemy
- soropg
- solv-protocol
- sushi
- sendit

**SCF project missing website** (8):
- relax
- the-starship-soroban
- crypto-link
- paysapp
- frost-implementation
- wally
- timed-transactions-api
- sendit


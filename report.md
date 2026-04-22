# Stellar Ecosystem Data Report

> Auto-generated on 2026-04-22

## Summary

| Metric | Count |
|--------|------:|
| Total projects | **672** |
| SCF-funded projects | 577 |
| Community projects | 95 |
| Audited projects | 48 |

## Data Coverage

| Field | Count | Coverage |
|-------|------:|---------:|
| description | 665/672 | 99% |
| website | 664/672 | 98.8% |
| blog | 245/672 | 36.5% |
| x | 484/672 | 72% |
| linkedin | 375/672 | 55.8% |
| discord | 205/672 | 30.5% |
| telegram | 143/672 | 21.3% |
| youtube | 162/672 | 24.1% |
| instagram | 111/672 | 16.5% |
| reddit | 12/672 | 1.8% |
| tiktok | 27/672 | 4% |
| linktree | 5/672 | 0.7% |
| github | 495/672 | 73.7% |
| category | 583/672 | 86.8% |
| tags | 666/672 | 99.1% |
| operating_region | 664/672 | 98.8% |
| based_in | 575/672 | 85.6% |

## Enrichment vs SCF Airtable

Per-project comparison of our **672** projects (incl. **95** community projects not in SCF) against **580** in SCF Airtable:

| Field | We Added | We Modified |
|-------|------:|------:|
| description | +117 | 548 |
| website | +134 | 530 |
| github | +113 | 382 |
| x | +200 | 284 |
| linkedin | +171 | 204 |
| discord | +96 | 109 |
| based_in | +99 | 476 |
| blog | +245 | 0 |
| telegram | +143 | 0 |
| youtube | +162 | 0 |
| instagram | +111 | 0 |
| reddit | +12 | 0 |
| tiktok | +27 | 0 |
| linktree | +5 | 0 |

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
| Tracked projects | 447 | 449 |
| Active last week | 113 | 199 |
| Active last month | 175 | 256 |
| Active last 3 months | 231 | 299 |
| Active last year | 309 | 365 |

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
| crawler | 1069 |
| website | 1614 |
| airtable | 3394 |
| agent:project-enricher | 7 |
| schedule | 1 |
| agent:content-linker:approved | 3 |
| soroban_security | 67 |

## Needs Review

15 items need attention.

**description empty** (7):
- xbid-ai
- soropg
- nethermind
- solv-protocol
- alchemy
- sushi
- sendit

**SCF project missing website** (8):
- frost-implementation
- relax
- wally
- crypto-link
- paysapp
- the-starship-soroban
- timed-transactions-api
- sendit


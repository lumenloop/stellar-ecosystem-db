# Stellar Ecosystem Data Report

> Auto-generated on 2026-05-11

## Summary

| Metric | Count |
|--------|------:|
| Total projects | **728** |
| SCF-funded projects | 610 |
| Community projects | 118 |
| Audited projects | 49 |

## Data Coverage

| Field | Count | Coverage |
|-------|------:|---------:|
| description | 711/728 | 97.7% |
| website | 720/728 | 98.9% |
| blog | 247/728 | 33.9% |
| x | 513/728 | 70.5% |
| linkedin | 388/728 | 53.3% |
| discord | 211/728 | 29% |
| telegram | 146/728 | 20.1% |
| youtube | 163/728 | 22.4% |
| instagram | 120/728 | 16.5% |
| reddit | 16/728 | 2.2% |
| tiktok | 31/728 | 4.3% |
| linktree | 5/728 | 0.7% |
| github | 508/728 | 69.8% |
| category | 638/728 | 87.6% |
| tags | 712/728 | 97.8% |
| operating_region | 700/728 | 96.2% |
| based_in | 605/728 | 83.1% |

## Enrichment vs SCF Airtable

Per-project comparison of our **728** projects (incl. **118** community projects not in SCF) against **633** in SCF Airtable:

| Field | We Added | We Modified |
|-------|------:|------:|
| description | +134 | 577 |
| website | +161 | 559 |
| github | +130 | 378 |
| x | +229 | 284 |
| linkedin | +185 | 203 |
| discord | +102 | 109 |
| based_in | +128 | 477 |
| blog | +247 | 0 |
| telegram | +146 | 0 |
| youtube | +163 | 0 |
| instagram | +120 | 0 |
| reddit | +16 | 0 |
| tiktok | +31 | 0 |
| linktree | +5 | 0 |

*"Added" = we filled a field SCF didn't have. "Modified" = SCF had a value, we store a different one.*

## SCF Project Coverage

Of **610** SCF-funded projects:

| Field | Count | Coverage |
|-------|------:|---------:|
| awarded_total | 557/610 | 91.3% |
| awarded_round | 589/610 | 96.6% |
| submission_urls | 589/610 | 96.6% |
| website | 602/610 | 98.7% |
| github | 453/610 | 74.3% |

*Gaps are mostly early-round projects (SCF #1-4) that predate the submissions tracking system, so per-submission budget and round data is unavailable.*

## Ecosystem Activity

*Based on last GitHub push and last tweet from tracked accounts.*

| Period | GitHub | Twitter |
|--------|------:|--------:|
| Tracked projects | 461 | 477 |
| Active last week | 143 | 204 |
| Active last month | 184 | 277 |
| Active last 3 months | 248 | 319 |
| Active last year | 320 | 390 |

## Audit Data

**49** projects audited with **68** reports.

*Audit data provided by [Soroban Security](https://sorobansecurity.com).*

| Auditor | Reports |
|---------|---------:|
| Veridise | 23 |
| OtterSec | 10 |
| certora | 10 |
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
| website | 1563 |
| submissions | 601 |
| airtable | 3822 |
| crawler | 782 |
| agent:airtable-sync:approved | 154 |
| agent:conflicts:approved | 4 |
| agent:conflict-resolver | 34 |
| admin | 46 |
| schedule | 2 |
| agent:content-linker:approved | 27 |
| agent | 10 |
| admin:scf_41_attribution | 1 |
| agent:project-enricher | 46 |
| agent:curator:approved | 2 |
| agent:project-enricher:approved | 36 |
| agent:curator | 7 |
| soroban_security | 68 |

## Needs Review

25 items need attention.

**SCF project missing website** (8):
- wally
- relax
- the-starship-soroban
- timed-transactions-api
- crypto-link
- sendit
- paysapp
- frost-implementation

**description empty** (17):
- figure
- mesh
- merkl
- coinme
- kalien
- sendit
- securrency
- akuna
- privy
- velo
- novatti
- rehive
- pyth
- ondo
- soropg
- volta
- xbid-ai


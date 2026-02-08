# Stellar Ecosystem Database

An open, structured dataset of **646 projects** building on the [Stellar](https://stellar.org) network — aggregated from multiple sources into a single, organized repository.

## What's Inside

```
projects/              # One YAML file per project (646 files)
report.md              # Auto-generated data completeness report
```

Each project file contains:

- **Identity** — name, slug, description, aliases
- **Links** — website, GitHub, X/Twitter, Discord, Telegram, LinkedIn, YouTube, and more
- **Attributes** — category, tags, operating regions, base location
- **SCF Data** — awarded rounds, total funding, submission URLs (for SCF-funded projects)
- **Mainnet** — token codes, contract addresses, audit reports

### Example

```yaml
title: Blend
slug: blend
description: Decentralized lending and borrowing protocol built on Stellar/Soroban
links:
  website:
    - blend.capital
  github:
    - github.com/blend-capital
  x:
    - blend_capital
attributes:
  category: Financial Protocols
  based_in: United States
scf:
  awarded_total: 575000
  awarded_round:
    - 27
    - 29
  submission_urls:
    - communityfund.stellar.org/submissions/recDqJi36pzlCON33
    - communityfund.stellar.org/submissions/recywmTn9l6tmxqLx
mainnet:
  audits:
    - name: Blend Protocol Audit
      url: https://github.com/AuditOne/...
      date: '2024-06-01'
      auditor: OtterSec
```

## Data Coverage

See [report.md](report.md) for the full auto-generated report. Key highlights:

| Field | Coverage |
|-------|----------|
| Description | 99.7% |
| Website | 98.6% |
| GitHub | 73.5% |
| X/Twitter | 67.2% |
| Category | 88.4% |
| Based in | 87.0% |

**577** projects are SCF-funded, **69** are community-contributed.

## Data Sources

| Source | Description |
|--------|-------------|
| [SCF](https://communityfund.stellar.org) | Stellar Community Fund — project metadata, submission records, funding data |
| [GitHub](https://github.com) | Repository stats, commit activity, contributors |
| [X/Twitter](https://x.com) | Account metadata, posting activity, location inference |
| [Soroban Security](https://sorobansecurity.com) | Smart contract audit reports for Soroban projects |
| Community | Manual contributions and corrections |

## Ecosystem Activity

Based on the latest tracked data:

| Period | GitHub (active) | Twitter (active) |
|--------|------:|--------:|
| Last week | 30 | 137 |
| Last month | 48 | 202 |
| Last 3 months | 72 | 254 |
| Last year | 114 | 317 |

## Usage

Each project is a standalone YAML file — easy to parse in any language:

```python
import yaml, glob

projects = []
for path in glob.glob("projects/*.yaml"):
    with open(path) as f:
        projects.append(yaml.safe_load(f))

# Find active SCF projects with GitHub
scf_with_github = [p for p in projects if p.get("scf") and p.get("links", {}).get("github")]
print(f"{len(scf_with_github)} SCF projects with GitHub repos")
```

## Contributing

This repository is automatically synced from the directory-sync pipeline. To suggest corrections or additions:

1. Open an issue describing the change
2. Or submit a PR modifying the relevant YAML file in `projects/`

External changes are auto-imported via webhook and merged with the intermediary database.

## License

This dataset is provided as a public good for the Stellar ecosystem. Data is aggregated from public sources.

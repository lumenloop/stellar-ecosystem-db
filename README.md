# Stellar Ecosystem Database

_Ecosystem DB Proposed by Lumen Loop_

The Stellar Ecosystem Database is a community-driven, open data initiative designed to provide the most up-to-date information on projects being built on the Stellar network and beyond. By merging data from multiple sources—including Lumen Loop DB, Stellar Light DB, the SCF website, and SCF Airtables—this project aims to create a single, organized repository of project details that is both transparent and accessible.

## Advantages of the Ecosystem DB

- **Up-to-date Information:**  
  Real-time visibility into what has been and is currently being built on Stellar.

- **Open Data:**  
  All project data is publicly available for anyone to use, analyze, or build upon.

- **Community-Driven:**  
  Contributions and suggestions from the community guide ongoing improvements and updates.

- **Inclusive of All Data:**  
  Not limited to data from the Stellar Community Fund (SCF); projects outside of SCF are represented as well.

- **Structured Metadata:**  
  Development of standardized attributes and categories to organize projects efficiently.

- **On-Chain Metrics:**  
  Integration of blockchain data points, such as tokens and contracts linked to projects.

## Project Updates and Workflow

Recent improvements and updates to the database include:

- **Data Integration:**  
  Combined datasets from Lumen Loop DB, Stellar Light DB, the SCF website, and various SCF Airtables (Soroban, SCF, OSO).

- **Working Group Formation:**  
  An Ecosystem DB working group was launched to steer and oversee database enhancements.

- **Standardizing Categories & Tags:**  
  Initiatives to coordinate and standardize project categories, tags, and attributes have been implemented.

- **Data Verification:**  
  Outreach was conducted to project teams to resolve conflicting data and verify details.

- **Content Enhancements:**  
  Project descriptions were updated for completeness, relevancy, and objectivity. External links (websites, repos, social media) were verified and enhanced; several new social fields were introduced.

- **SCF Data Refinement:**  
  Projects within the SCF dataset were re-evaluated, with some split or combined based on renames or duplicates, and submissions were reassigned accordingly.

- **Feedback Integration:**  
  A [document](https://docs.google.com/spreadsheets/d/1JDBQVIIbiP86IgH1RX9VHDpsUVCj8Xha5NEYBr9mH5c/edit?usp=sharing) listing suggestions and errors from the SCF data was shared with the SCF team to support ongoing improvements.

## Data Metrics Comparison (as of April 11th 2025)

The following tables summarize key data points comparing the legacy SCF data with the updated Ecosystem DB values:

### Project Metadata

| **Field**       | **SCF Data** | **Ecosystem DB** |
|-----------------|:------------:|:----------------:|
| **Projects**    | 459          | 530              |
| **Other Names** |  —          | 179              |
| **Websites**    | 416          | 518              |
| **Descriptions**| 433            | 527              |

### Social & Communication Metrics

#### Primary Social Channels

| **Field**   | **SCF Data** | **Ecosystem DB** |
|-------------|:------------:|:----------------:|
| **Github**  | 286          | 377              |
| **X** (formerly Twitter) | 193  | 344         |
| **LinkedIn**| 134          | 244              |
| **Discord** | 80           | 122              |

#### Additional Social Platforms (Ecosystem DB Only)

| **Field**   | **Count** |
|-------------|----------:|
| **Youtube** | 106       |
| **Instagram** | 110     |
| **Reddit**  | 21        |
| **Tiktok**  | 18        |

#### Other Categories (Ecosystem DB Only)

| **Field**          | **Count** |
|--------------------|----------:|
| **Telegram**       | 88        |
| **Parent Projects**| 60        |
| **Blogs**          | 214       |

*Note: These figures serve as snapshots comparing the legacy data from SCF with the refined metrics in the Ecosystem DB and may evolve over time.*

## File Format Specification

Each project in the database follows a YAML-based file format. Below is an example entry:

```yaml
title: Giveth
other_names: null
parent: null
description: Giveth is a community-driven platform that leverages blockchain
  technology to facilitate zero-fee cryptocurrency donations to vetted projects,
  nonprofits, and charities.
links:
  website: https://giveth.io
  blog: https://blog.giveth.io/
  x: https://x.com/Giveth
  linkedin: null
  discord_server: https://discord.giveth.io/
  telegram: null
  youtube: https://youtube.com/givethio
  instagram: https://instagram.com/giveth.io/
  reddit: https://reddit.com/r/giveth
  tiktok: null
  github: https://github.com/Giveth
linktree: null
attributes:
  category: Sustainability & Public Goods
  tags: []
  smart_contracts: false
  regions_services: null
  country: " Spain"
images:
  icon: null
  thumbnail: https://v5.airtableusercontent.com/v3/u/39/39/1744048800000/dBTCDVWuTjTMCW_C8QvVHw/UJ170-zby1XS_SKZoIkx1-c-JvPbWVat9cpROxevgf2VCUEmqN1iVEhW5mgFX8fClfB5JrLpLqjdvbmyU4AU3ch593UMzH8-oBWeAhnnYmcIhgwc2s-2QxU0E3Hi_mzCjc-2_xZbV3Sk2ePgJWXORcpK7bolw7nHBWrn1iVHwd5YekyeQUwXLxprgZh3fti1/pgIFcsZSUol9tE3r_xrIq93TsFUcptZgXBJ3_GeNzsE
  banner: null
scf:
  awarded_submissions:
    - Giveth
  awarded_submissions_url:
    - https://communityfund.stellar.org/dashboard/submissions/rechcT1UmtJlod9ec
  awarded_round:
    - "SCF #28"
  awarded_total: 50000
mainnet:
  live: true
  tokens: []
  contracts: []
  audits: []
```

## Getting Started

To set up and run the Stellar Ecosystem Database locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/lumenloop/stellar-ecosystem-db.git
   cd stellar-ecosystem-db
   ```
## Review Documentation
Familiarize yourself with the file format, the data model, and the contribution guidelines.

## Contribute
Contributions are welcome! Whether you’re suggesting improvements or submitting new projects, please review our [Contribution Guidelines](CONTRIBUTING.md) and open an issue or pull request on GitHub.

## Future Enhancements

- **Data Standardization:**  
  Continued work on harmonizing project categories, tags, and additional attributes.

- **Increased On-Chain Data Points:**  
  Incorporate new on chain data points like issuers, tomls, tokens, contracts.

- **Expanded Data Sources:**  
  Integration of additional project repositories and community sources to ensure comprehensive coverage.
  
- **Automated Data Integration:**  
  Implement automated processes to update the database from external datasets, ensuring the information remains current and reducing the need for manual data entry.

- **Working Group Collaboration:**  
  Collaborate with the working group to identify, verify, and update missing projects and database fields for enhanced completeness and quality.

- **Community Engagement:**  
  Maintaining an open dialogue with project teams and contributors to keep data accurate and up-to-date.

## Acknowledgments
A special thank you to everyone who has contributed to the creation and refinement of the Stellar Ecosystem Database, including the teams at Stellar Light and the Stellar Community Fund, as well as all community members who provided feedback and updates.

# Available .VEGAS One-Word Domains (11,920)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C920%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vegas one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,920 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,920 domains · **Median ask:** $46.02 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/vegas`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vegas?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vegas.csv">CSV</a> / <a href="./vegas.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VEGAS search](https://unique.domains/domains/tld/vegas?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VEGAS search](https://unique.domains/domains/tld/vegas?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VEGAS one-word domain catalog.

### Files

- `vegas.csv` — public CSV extract (1,000 rows)
- `vegas.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vegas-oneword-domains/main/vegas.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| Sony.vegas     | available | $64.98    | —             | 86             | 67     | 4      | namecheap   |
| barup.vegas    | available | $29.99    | —             | 82             | 2      | 6      | name.com    |
| geton.vegas    | available | $29.99    | —             | 82             | 10     | 6      | name.com    |
| getup.vegas    | available | $29.99    | —             | 82             | 14     | 6      | name.com    |
| matcha.vegas   | available | $29.99    | —             | 86             | 39     | 6      | name.com    |
| Apples.vegas   | available | $64.98    | —             | 90             | 16     | 6      | namecheap   |
| playin.vegas   | available | $29.99    | —             | 80             | 10     | 7      | name.com    |
| toneup.vegas   | available | $29.99    | —             | 80             | 5      | 7      | name.com    |
| makeit.vegas   | available | $29.99    | —             | 82             | 22     | 7      | name.com    |
| pierogi.vegas  | available | $29.99    | —             | 82             | 7      | 7      | name.com    |
| leaveon.vegas  | available | $29.99    | —             | 80             | 1      | 8      | name.com    |
| messages.vegas | available | $12.99    | $43.99        | 80             | 16     | 8      | namesilo    |
| Snickers.vegas | available | $64.98    | —             | 80             | 10     | 8      | namecheap   |
| rumcake.vegas  | available | $29.99    | —             | 81             | 3      | 8      | name.com    |
| claim.vegas    | resell    | —         | —             | 78             | 30     | 5      | Dynadot Inc |
| agents.vegas   | premium   | $250      | —             | 56             | 50     | 6      | name.com    |
| RedSox.vegas   | available | $64.98    | —             | 72             | 60     | 7      | namecheap   |
| injury.vegas   | resell    | —         | —             | 68             | 16     | 6      | Dynadot Inc |
| WiFi.vegas     | premium   | $280      | $139.93       | 83             | 37     | 5      | namecheap   |
| Books.vegas    | available | $64.98    | —             | 52             | 49     | 5      | namecheap   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,920 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vegas?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vegas?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely focused on one-word .vegas domains. The names range from generic and campaign-friendly options like finals.vegas, jewels.vegas, popup.vegas, and matcha.vegas to sharper, less intuitive strings such as acup.vegas or barup.vegas. For founders, the main question is whether a name is memorable, easy to say, and specific enough to feel intentional without becoming limiting. For investors, the key is buy-in discipline: a median ask of 46.02 keeps attention on low-cost entries, but resale and spread data are not established here, so quality judgment matters more than headline price alone. Be stricter with trademark exposure on names like Sony.vegas.

- One-word .vegas names only, from generic to coined
- Median ask is 46.02 across 11,916 domains
- Prioritize clarity, recall, and local fit to Las Vegas
- Avoid obvious trademark terms such as Sony.vegas

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VEGAS One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VEGAS page](https://unique.domains/domains/tld/vegas?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vegas_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

# Available .LA One-Word Domains (11,547)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C547%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .la one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,547 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,547 domains · **Median ask:** $92.48 · **High-demand under $2,500:** 35

**Last updated:** 2026-08-11
**Canonical page:** `https://unique.domains/domains/tld/la`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/la?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./la.csv">CSV</a> / <a href="./la.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LA search](https://unique.domains/domains/tld/la?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LA search](https://unique.domains/domains/tld/la?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LA one-word domain catalog.

### Files

- `la.csv`, public CSV extract (1,000 rows)
- `la.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/la-oneword-domains/main/la.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                       |
| --------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------------- |
| cot.la    | available | $27.99     | $27.99        | high           | low    | 3      | namesilo                        |
| high.la   | resell    | $2,309.78  | —             | medium         | low    | 4      | .LA Founders Premium Program    |
| her.la    | premium   | $1,124.09  | —             | medium         | low    | 3      | name.com                        |
| Eid.la    | available | $27.99     | $27.99        | high           | low    | 3      | namesilo                        |
| line.la   | resell    | $1,776.75  | —             | high           | medium | 4      | .LA Founders Premium Program    |
| xxv.la    | premium   | $39        | $46.99        | medium         | low    | 3      | name.com                        |
| MMR.la    | available | $27.99     | $27.99        | high           | low    | 3      | namesilo                        |
| built.la  | resell    | $1,776.75  | —             | high           | low    | 5      | VIPDomains.LA  Founders Program |
| loft.la   | premium   | $20,728.75 | —             | medium         | low    | 4      | GoDaddy.com, Inc.               |
| NWO.la    | available | $41.98     | —             | medium         | low    | 3      | namecheap                       |
| proud.la  | resell    | $1,006.82  | —             | high           | low    | 5      | VIPDomains.LA  Founders Program |
| sort.la   | premium   | $27.99     | $27.99        | high           | low    | 4      | namesilo                        |
| xci.la    | available | $32.98     | $41.98        | low            | low    | 3      | namecheap                       |
| center.la | resell    | $1,762.54  | —             | high           | low    | 6      | Porkbun, LLC                    |
| veer.la   | premium   | $27.99     | $27.99        | high           | low    | 4      | namesilo                        |
| xcv.la    | available | $32.98     | $41.98        | low            | low    | 3      | namecheap                       |
| coming.la | resell    | $1,125.28  | —             | high           | low    | 6      | VIPDomains.LA  Founders Program |
| smell.la  | premium   | $27.99     | $27.99        | high           | low    | 5      | namesilo                        |
| arid.la   | available | $32.98     | $41.98        | low            | low    | 4      | namecheap                       |
| purple.la | resell    | $2,309.78  | —             | medium         | medium | 6      | VIPDomains.LA  Founders Program |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,547 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 35 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/la?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/la?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection brings together 10,608 one-word .LA domain names, spanning everyday nouns, compound words, and inventive coinages such as stirup.la, jetblack.la, and flaxseed.la. The median asking price across the set is $119.43, offering a practical reference point for founders comparing brandable options and investors assessing pricing patterns within this TLD. Updated daily, the mix ranges from simple, dictionary-style names to more distinctive, brandable picks.

- 10,608 one-word .LA domain names in this set
- Median asking price: $119.43
- Mix of everyday words and inventive coinages
- Updated daily to reflect current listings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LA One-Word Domains*. Version 2026-08-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LA page](https://unique.domains/domains/tld/la?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

# Available .LA One-Word Domains (10,053)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C053%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .la one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,053 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,053 domains

**Last updated:** 2026-04-26  
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

- `la.csv` — public CSV extract (1,000 rows)
- `la.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/la-oneword-domains/main/la.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                    |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------- |
| IsleofMan.la | available | $41.98    | —             | 62             | 91     | 11     | namecheap                    |
| las.la       | resell    | —         | —             | 48             | 98     | 3      | LA Domain Names              |
| common.la    | premium   | $1,954.42 | —             | 71             | 36     | 6      | name.com                     |
| RedSox.la    | available | $41.98    | —             | 72             | 60     | 7      | namecheap                    |
| farmers.la   | resell    | —         | —             | 54             | 59     | 7      | LA Domain Names              |
| regions.la   | available | $39       | —             | 64             | 59     | 7      | name.com                     |
| robots.la    | resell    | —         | —             | 62             | 47     | 6      | LA Domain Names              |
| gods.la      | available | $39       | —             | 72             | 27     | 4      | name.com                     |
| lets.la      | resell    | —         | —             | 77             | 39     | 4      | LA Domain Names              |
| Iknow.la     | available | $41.98    | —             | 58             | 26     | 6      | namecheap                    |
| spectra.la   | resell    | —         | —             | 62             | 34     | 7      | .LA Founders Premium Program |
| reports.la   | available | $39       | —             | 58             | 24     | 7      | name.com                     |
| etc.la       | resell    | —         | —             | 58             | 34     | 3      | .LA Founders Premium Program |
| echoes.la    | available | $27.99    | $27.99        | 56             | 24     | 6      | namesilo                     |
| Cats.la      | resell    | —         | —             | 59             | 33     | 4      | .LA Founders Premium Program |
| products.la  | available | $39       | —             | 60             | 23     | 8      | name.com                     |
| partners.la  | resell    | —         | —             | 61             | 32     | 8      | LA Domain Names              |
| CapeCod.la   | available | $41.98    | —             | 78             | 22     | 8      | namecheap                    |
| spaces.la    | resell    | —         | —             | 54             | 30     | 6      | GoDaddy.com, Inc.            |
| brothers.la  | available | $39       | —             | 60             | 22     | 8      | name.com                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 10,053 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/la?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/la?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LA One-Word Domains*. Version 2026-04-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LA page](https://unique.domains/domains/tld/la?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_la_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

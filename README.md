# Available .ONG One-Word Domains (12,580)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C580%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ong one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,580 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,580 domains · **Median ask:** $35.06 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/ong`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ong?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ong.csv">CSV</a> / <a href="./ong.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ONG search](https://unique.domains/domains/tld/ong?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ONG search](https://unique.domains/domains/tld/ong?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ONG one-word domain catalog.

### Files

- `ong.csv` — public CSV extract (1,000 rows)
- `ong.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ong-oneword-domains/main/ong.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| insight.ong      | available | $16.99    | —             | 76             | 69     | 8      | name.com  |
| Books.ong        | premium   | $70       | $35           | 52             | 49     | 5      | namecheap |
| donuts.ong       | available | $16.99    | —             | 54             | 62     | 6      | name.com  |
| skills.ong       | premium   | $625      | —             | 58             | 47     | 6      | name.com  |
| travelers.ong    | available | $16.99    | —             | 58             | 61     | 9      | name.com  |
| videos.ong       | premium   | $62.50    | —             | 52             | 30     | 6      | name.com  |
| agents.ong       | available | $16.99    | —             | 56             | 50     | 6      | name.com  |
| investors.ong    | premium   | $62.50    | —             | 60             | 23     | 9      | name.com  |
| Ryan.ong         | available | $24.98    | —             | 60             | 44     | 4      | namecheap |
| blogs.ong        | premium   | $62.50    | —             | 52             | 21     | 5      | name.com  |
| matcha.ong       | available | $16.99    | —             | 86             | 39     | 6      | name.com  |
| mathematics.ong  | premium   | $62.50    | —             | 68             | 19     | 11     | name.com  |
| lets.ong         | available | $16.99    | —             | 77             | 39     | 4      | name.com  |
| dads.ong         | premium   | $62.50    | —             | 60             | 17     | 4      | name.com  |
| prompts.ong      | available | $16.99    | —             | 54             | 39     | 7      | name.com  |
| meals.ong        | premium   | $625      | —             | 68             | 15     | 5      | name.com  |
| stories.ong      | available | $16.99    | —             | 58             | 36     | 7      | name.com  |
| appreciation.ong | premium   | $62.50    | —             | 88             | 13     | 12     | name.com  |
| aliens.ong       | available | $16.99    | —             | 56             | 35     | 6      | name.com  |
| seas.ong         | premium   | $625      | —             | 58             | 13     | 4      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,580 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ong?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ong?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .ong domains. The naming style is broad: literal words such as boat.ong and lunch.ong, expressive terms such as hype.ong and cute.ong, and longer phrases such as pyjamaparty.ong. For founders, the main question is whether a name is clear, memorable, and ownable for the exact market you want to serve. For investors, the key issue is how much buyer demand a .ong name can realistically attract at its ask. The median ask here is 35.06, which keeps entry price low, but extension fit matters more than word quality alone when comparing these domains.

- All domains in this set use the .ong extension
- Median ask across the selection is 35.06
- Word styles range from literal to expressive to phrase-based
- Check extension fit and trademark exposure before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ONG One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ONG page](https://unique.domains/domains/tld/ong?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ong_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

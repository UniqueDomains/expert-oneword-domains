# Available .EXPERT One-Word Domains (80,357)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-80%2C357%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .expert one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **80,357 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 80,357 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/expert`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/expert?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./expert.csv">CSV</a> / <a href="./expert.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .EXPERT search](https://unique.domains/domains/tld/expert?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .EXPERT search](https://unique.domains/domains/tld/expert?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .EXPERT one-word domain catalog.

### Files

- `expert.csv` — public CSV extract (10,000 rows)
- `expert.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/expert-oneword-domains/main/expert.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                          |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------------ |
| Abe.expert       | available | $82.48    | —             | 62             | 92     | 3      | namecheap                                                          |
| oasis.expert     | resell    | —         | —             | 68             | 96     | 5      | Domain Science Kutatási Szolgáltató Korlátolt Felelősségű Társaság |
| cycling.expert   | premium   | $128.70   | $128.70       | 86             | 84     | 7      | namecheap                                                          |
| zouk.expert      | available | $54.98    | —             | 88             | 88     | 4      | namecheap                                                          |
| linux.expert     | resell    | —         | —             | 74             | 92     | 5      | Sav.com, LLC - 27                                                  |
| degree.expert    | premium   | $520      | $520          | 60             | 80     | 6      | namecheap                                                          |
| arcade.expert    | available | $82.48    | —             | 84             | 88     | 6      | namecheap                                                          |
| nutrition.expert | resell    | —         | —             | 64             | 92     | 9      | Global Domains International, Inc. DBA DomainCostClub.com          |
| cooling.expert   | premium   | $85.80    | $85.80        | 74             | 76     | 7      | namecheap                                                          |
| abcs.expert      | available | $82.48    | —             | 66             | 88     | 4      | namecheap                                                          |
| trans.expert     | resell    | —         | —             | 92             | 88     | 5      | PDR Ltd. d/b/a PublicDomainRegistry.com                            |
| guidance.expert  | premium   | $520      | $520          | 64             | 76     | 8      | namecheap                                                          |
| glazing.expert   | available | $82.48    | —             | 62             | 88     | 7      | namecheap                                                          |
| mama.expert      | resell    | —         | —             | 76             | 88     | 4      | Sav.com, LLC - 28                                                  |
| key.expert       | premium   | $123.75   | $123.75       | 80             | 43     | 3      | name.com                                                           |
| airtaxi.expert   | available | $82.48    | —             | 58             | 88     | 8      | namecheap                                                          |
| civility.expert  | resell    | —         | —             | 68             | 88     | 8      | GoDaddy.com, LLC                                                   |
| farm.expert      | premium   | $520      | $520          | 72             | 37     | 4      | namecheap                                                          |
| motel.expert     | available | $82.48    | —             | 86             | 84     | 5      | namecheap                                                          |
| vitality.expert  | resell    | —         | —             | 64             | 88     | 8      | Dynadot Inc                                                        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 80,357 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/expert?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/expert?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .EXPERT One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EXPERT page](https://unique.domains/domains/tld/expert?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_expert_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

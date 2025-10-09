# robots_txt-optout-dataset

# Robots.txt Opt-out Dataset (BEDC Top-100, 2024)

This repository contains the dataset and clustering results used in the study:
**"Clustering Web Crawler Opt-Out Strategies: A Typology Based on Robots.txt Data for Sustainable Data Access"**
by Bo-Ren Cheng & Chiang-Yu Cheng .

---

## 📘 1. Data Collection
**File:** `data_collection/robots_txt_results_FINAL.xlsx`

- 98 valid robots.txt files from the BEDC Top-100 global websites (2024)
- Parsed into 8 structured features:
  - `ai_block_count`
  - `blocks_search_engines`
  - `global_disallow_root`
  - `disallow_scope_ratio`
  - `crawl_delay_norm`
  - `ai_only_block`
  - `wildcard_usage`
  - `sitemap_present`

---

## 🧮 2. Clustering Results
**Folder:** `clustering_results/`

Contains three CSV files representing the websites in each opt-out strategy:

| File | Cluster Label | Description |
|------|----------------|-------------|
| `websites_full-opt-out.csv` | A | Full Opt-out (comprehensive blocking) |
| `websites_partial-opt-out-ai-targeted.csv` | B | Partial Opt-out: AI-targeted |
| `websites_partial-opt-out-rate-limited.csv` | C | Partial Opt-out: Rate-limited |

---

## 📊 3. Analysis Summary
**File:** `analysis_summary/summary_all_features_with_smd.csv`

- Summarizes feature statistics (mean, SD, SMD) across clusters.

---

## 🧾 Citation
If you use this dataset, please cite:

> Cheng, B.-R., & Cheng, C.-Y. . *Robots.txt opt-out dataset (BEDC Top-100, 2024)* [Data set]. GitHub. [https://github.com/yourname/robots-optout-dataset](https://github.com/Raycheng0629/robots_txt-optout-dataset)

-

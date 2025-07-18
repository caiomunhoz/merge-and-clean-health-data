# 📊 Merging & Cleaning Pipeline

This repository contains a Jupyter Notebook and supporting Python code written as practice for the **DataCamp Data Engineer Certification**. The task simulates a real-world data engineering scenario in which multiple datasets from a health-tracking platform need to be merged and cleaned for use in analysis or modeling.

---

## 📋 Task Description

You’ve been hired to assist the data science team at **1001-Experiments**, a company conducting health experiments using data collected from wearable devices, supplements, and user demographics. The company is currently handling four separate datasets:

- `user_health_data.csv` — Daily health metrics and wearable data (per user)
- `supplement_usage.csv` — Records of supplement intake
- `experiments.csv` — Metadata about supplement-related experiments
- `user_profiles.csv` — Demographic and contact details of users

Managing these datasets independently is inefficient and error-prone. Your task is to **clean and merge** them into a single, coherent DataFrame with the following goals:

- Consolidate data per user across all available sources
- Standardize column formats
- Engineer new features (e.g. age groups, grams dosage)
- Prepare the dataset for downstream analysis
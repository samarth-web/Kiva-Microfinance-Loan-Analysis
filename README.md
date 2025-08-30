# Kiva-Microfinance-Loan-Analysis-
## View Interactive Kaggle Workbook here: https://www.kaggle.com/code/samarthj204/notebook85b0799694
Exploring global microfinance patterns (country, sector, loan size, funding/repayment) to highlight financial inclusion insights.
# Kiva Microfinance Loan Analysis — Predicting Funding Risk


## Overview
This project analyzes Kiva’s microfinance loans to identify patterns in funding success and to predict loans at risk of underfunding. It combines exploratory data analysis with machine learning (Logistic Regression and Random Forest) to support “Data Science for Good (Crowdfunding: Kiva)" decision-making and improve resource allocation.

## Key Results (Executive Summary)
- Underfunded loans are a small minority (~7%) but can be detected with **high recall (~76%)**.
- Trade-off: **low precision (~15%)** for underfunded loans → many false alarms.
- Fully funded loans show **very high precision (~97%)** with moderate recall (~68%).
- Funding risk concentrates in specific **sectors** (e.g., Agriculture, Retail) and **countries** (e.g., El Salvador, Kenya).
- Conclusion: The model works as an **early-warning system**, useful for triage; further tuning can reduce false positives.

## Dataset
- Source: Kiva “Data Science for Good” (Kaggle).
- https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding/code
- Note: The raw CSVs are large (>100MB) and **not included** in this repository.
- To reproduce:
  1. Download the dataset from Kaggle.
   2. Place files under `data/` (this folder is `.gitignore`’d).

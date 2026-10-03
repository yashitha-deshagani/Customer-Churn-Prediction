# Customer Churn Prediction

A machine learning project predicting which bank customers are likely to churn, using Python, SQL, and Scikit-learn — with every recommendation grounded in real calculated metrics.

## Overview

Using a 10,000-row dataset of bank customers, this project identifies which customers are at risk of leaving and what factors most strongly predict churn — then turns those findings into concrete retention recommendations.

## Problem Statement

Customer churn is expensive to replace, and businesses need to know who's at risk before they leave, not after. This project builds a full pipeline — from raw data to a trained classification model — that flags at-risk customers and explains *why* they're at risk, so retention efforts can be targeted rather than blanket.

## Tech Stack

| Layer | Tools |
|---|---|
| Data cleaning & analysis | Python, Pandas |
| Querying | SQL (SQLite) |
| Machine learning | Scikit-learn |
| Environment | Google Colab |

## Dataset

Bank Customer Churn dataset (10,000 rows, 14 columns): customer demographics (age, geography, gender), account info (balance, tenure, number of products, credit score), and the target variable `Exited` (1 = churned).

## Setup Instructions

1. Clone this repository
2. Open `churn_prediction.ipynb` in Google Colab or Jupyter
3. Upload `Churn_Modelling.csv` to your Colab session
4. Run cells sequentially

## Progress

**Week 1 — Data Pipeline (Complete):** Cleaned the dataset, loaded it into SQLite, and answered core business questions with SQL.

### Key Findings (Week 1)

- **Germany has by far the highest churn rate** (~32%) compared to Spain (16.67%) and France (16.15%) — customers in Germany are roughly twice as likely to leave as customers in either other country.
- **Churn rises sharply with age**: customers aged 50-59 churn at 56.04% — more than double the 40-49 group (30.79%) and over 7x the Under-30 group (7.56%). The strongest pattern in the data.
- **Inactive members churn nearly 2x as often as active ones** (26.85% vs. 14.27%), confirming engagement is a meaningful retention signal.
- **Churned customers had a higher average balance** ($91,108.54) than retained customers ($72,745.30) — the bank isn't just losing low-value customers, it's losing wealthier ones.
- **Tenure barely differs** between churned (4.93 years) and retained (5.03 years) customers — unlike age or activity, tenure alone isn't a strong churn predictor.

**Week 2 — Baseline Model:** Not yet started.

**Week 3 — Model Comparison & Tuning:** Not yet started.

**Week 4 — Interpretation & Recommendations:** Not yet started.

## Future Sections (to be added)

- Model performance (precision, recall, F1, confusion matrix)
- Feature importance
- Business recommendations backed by model results

## Tools

Python · Pandas · SQL · Scikit-learn

## Project Status

**In Progress** — Week 1 of 5 complete.

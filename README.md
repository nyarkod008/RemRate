# E-XGBoostRank

## An Engineered XGBoost-Weighted Ranking Model for Remittance Provider Comparison in the Ghana–China Financial Corridor

### Overview

E-XGBoostRank is a machine learning research project that develops an explainable ranking system for comparing remittance providers serving the Ghana–China financial corridor.

The system uses an engineered XGBoost learning-to-rank model combined with SHAP explainability to recommend the best provider based on:

* Exchange rate margin
* Transaction fees
* Delivery speed
* Provider reputation
* User preferences

The project aims to improve transparency and decision-making for Ghanaian traders, students, professionals, and families sending money to China.

---

## Research Objectives

1. Develop an engineered XGBoost ranking model (E-XGBoostRank).
2. Compare performance against standard XGBoost, Logistic Regression, and Rule-Based Ranking.
3. Explain recommendations using SHAP.
4. Evaluate statistical significance of improvements.

---

## Engineering Contributions

### Modify (M)

* Pairwise Learning-to-Rank objective
* Survey-derived feature weighting

### Remove (R)

* SHAP-based feature pruning
* Reduced inference time for mobile deployment

---

## Dataset

### Primary Data

* Web-scraped remittance provider information
* User preference surveys
* Informal agent interviews

### Secondary Data

* World Bank Remittance Prices Worldwide Dataset

---

## Evaluation Metrics

* NDCG@K
* AUC-PR
* AUC-ROC
* Macro F1 Score
* SHAP Feature Importance

---

## Project Structure

```text
e-xgboost-rank/
│
├── data/
├── notebooks/
├── src/
├── models/
├── results/
├── figures/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Reproducibility

* Python 3.10
* XGBoost 2.0.3
* SHAP 0.44.0
* Scikit-Learn 1.3.0

Random Seed:

```python
SEED = 2026
```

---

## Expected Contribution

This project is the first known application of an engineered XGBoost ranking framework with SHAP explainability for remittance provider recommendation in the Ghana–China corridor.

---

## Author

Nyarko Daniel
Student ID: 9031223

---

## Supervisor

Dr. E.O Osei

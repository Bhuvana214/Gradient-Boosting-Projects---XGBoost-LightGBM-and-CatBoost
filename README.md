# Gradient-Boosting-Projects---XGBoost-LightGBM-and-CatBoost
This repository contains two end-to-end machine learning projects completed as part of the Gradient Boosting Made Easy: XGBoost, LightGBM and Friends certification from 365 Data Science.
## Projects

### 1. Wine Quality Classification

File: wine_quality_classification.ipynb

| Detail | Info |
|---|---|
| Dataset | Wine Quality - Red and White merged - 6497 samples |
| Task | Binary Classification - Good wine (quality 7 and above) vs Bad wine |
| Models | XGBoost, LightGBM, CatBoost |
| Metric | F1 Score |

What this project covers:
- EDA: quality score distribution, correlation heatmap, feature boxplots
- Target transformation: raw scores to binary label
- Label encoding for wine type
- Class imbalance handling using scale_pos_weight, is_unbalance, and auto_class_weights
- Hyperparameter tuning with GridSearchCV and StratifiedKFold 5-fold
- Evaluation: F1 Score, confusion matrix, ROC-AUC, feature importance

---

### 2. Credit Rating Regression

File: credit_rating_regression.ipynb

| Detail | Info |
|---|---|
| Dataset | Credit Data - 400 samples, 10 features |
| Task | Regression - Predict continuous credit Rating |
| Models | XGBoost, LightGBM, CatBoost |
| Metric | Mean Absolute Error (MAE) |

What this project covers:
- EDA: rating distribution, categorical counts, correlation heatmap, scatter plots
- Preprocessing: drop ID column, label encode categorical columns, 80/20 train-test split
- Training with default settings and train time measurement
- Evaluation: MAE, RMSE, R2, actual vs predicted plots, residual plots, feature importance

Results (default settings):

| Model | MAE | Train Time |
|---|---|---|
| CatBoost | 11.27 | Slowest |
| XGBoost | 11.38 | Medium |
| LightGBM | 15.31 | Fastest |

Top feature in XGBoost: Limit (98.7% importance)

---

## Tech Stack

- Python
- XGBoost
- LightGBM
- CatBoost
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

---

## How to run

# Install dependencies
pip install xgboost lightgbm catboost scikit-learn pandas numpy matplotlib seaborn

# Open notebooks
jupyter notebook
```

Note: Always run notebooks from top to bottom using Kernel - Restart and Run All to avoid any variable errors.

---

## Certification

Gradient Boosting Made Easy: XGBoost, LightGBM and Friends - 365 Data Science - 2026

365 Data Science Certification - 2026

---

## Author

Bhuvana

Specializing in drug discovery machine learning, cheminformatics, and ADMET prediction.


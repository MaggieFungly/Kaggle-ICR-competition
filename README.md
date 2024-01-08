# Kaggle ICR Competition

This repository contains the models and code used in the [ICR Competition](https://www.kaggle.com/competitions/icr-identify-age-related-conditions/submissions). We employ two main modeling approaches:

## 1. [XGBoost Model](https://github.com/MaggieFungly/Kaggle-ICR-competition/blob/main/XGBoost.ipynb)
- The XGBoost model is fine-tuned using Optuna with a custom objective function, specifically designed to optimize balanced log loss. This tuning ensures the model is robust, especially for imbalanced datasets.

## 2. [Ensemble Tree Models](https://github.com/MaggieFungly/Kaggle-ICR-competition/blob/main/xgboost-lightgbm-logistic-regression.ipynb)
- We utilize an ensemble of tree-based models including XGBoost and LightGBM.
- A Logistic Regression model is used to stack predictions from both XGBoost and LightGBM, producing the final output.
- This ensemble approach leverages the strengths of each individual model to improve overall predictive performance.

# Explainable Machine Learning for Predicting Investment Participation: Analysing Investment Behaviour Using SHAP

## Overview

This project builds an explainable machine learning framework to predict whether a United States adult currently holds investments in stocks, bonds, or mutual funds outside of retirement accounts, based on demographic, financial, attitudinal, and behavioural characteristics.

The framework works in two phases. First, Logistic Regression, Random Forest, and XGBoost are trained and compared to classify respondents as investors or non-investors. Second, the best model is applied to current non-investors to estimate their investment propensity (how closely their profile resembles an investor), and SHAP is used to explain what drives each score. This helps financial organisations identify and prioritise investment-ready non-investors.

## Objectives

1. Identify the demographic, financial, attitudinal, and behavioural features that distinguish investors from non-investors.
2. Train and compare Logistic Regression, Random Forest, and XGBoost for predicting investment participation.
3. Select the best model using cross-validation ROC-AUC and evaluate it on a held-out test set.
4. Apply SHAP to explain predictions at global and individual levels.
5. Estimate and explain the investment propensity of current non-investors to support targeted financial outreach.

## Dataset

Link: https://www.finrafoundation.org/nfcs-data-and-downloads  — State-by-State Survey

## Technologies Used

- Python 3
- Google Colab
- pandas, NumPy
- scikit-learn
- XGBoost
- SHAP
- Matplotlib, Seaborn
- SciPy

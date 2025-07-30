# Dissertation Code: Economic, socio-developmental, and governance-related predictors of cross-national variation in homicide rates

This repository contains Python code used in my MSc dissertation for Applied Social Data Science at Trinity College Dublin. All analyses were done in Python 3.12.7 using Jupyter Notebooks.

## Files
- 'data_cleaning.ipynb': Deletes irrelevant variables, filters out countries with insufficient data, and imputes missing values for the remaining dataset.
- 'descriptives.ipynb': Produces basic descriptive statistics for each variable, a correlation matrix, a Variance Inflation Factor (VIF) table, and visualizations of the dependent variable.
- 'panel_regression.ipynb': Runs the fixed-effects panel regression with country and year effects.
- 'RF_robustness.ipynb': Trains a Random Forest model, computes feature importances, visualizes Partial Dependence Plots (PDPs), and conducts three robustness checks (cross-validation, permutation importance, and ridge regression).

## Data
All data come from public sources:
- UNODC (homicide rates)
- World Development Indicators (WDI)
- Worldwide Governance Indicators (WGI)

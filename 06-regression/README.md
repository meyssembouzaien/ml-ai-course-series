# 06 — Regression


## What this chapter covers

The regression counterpart to the classification chapters — predicting
continuous numeric values instead of categories.

- Classification vs regression: predicting a number vs a category
- **Simple linear regression**: the equation `y = ax + b`, residuals, and
  Mean Squared Error (MSE) as the objective to minimize
- **Multiple linear regression**: predicting from several features at once
  (e.g. house price from surface, bedrooms, and age)
- **Polynomial regression**: modeling curved relationships, and the risk of
  overfitting at high polynomial degrees
- Evaluation metrics: MSE, RMSE, MAE, and R² — what each one means and when
  to use which
- Train/test split and the overfitting/underfitting trade-off, specific to
  regression
- **Regularization**: Ridge (L2) and Lasso (L1) — how they penalize large
  coefficients, and how Lasso performs automatic feature selection
- A full model comparison table and recommended workflow
- Practice exercises: car price prediction, sales forecasting, and comparing
  regularized vs unregularized models

Pairs naturally with chapter 05 as the two supervised-learning pillars.

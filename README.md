🚀 Sales Prediction Analysis
Predict sales using feature engineering, time-aware preprocessing, and multiple regression models. This repository contains an end‑to‑end Jupyter Notebook that explores the dataset, builds reusable preprocessing pipelines, and compares models with time‑based cross‑validation to produce robust sales forecasts.

✨ Overview
This project explores a sales dataset (train.csv), creates features (date, aggregated customer/product, lags/rolls), builds reproducible preprocessing pipelines, and evaluates multiple regression models with time-aware cross-validation. The goal is a production-ready candidate model with explainability and an inference workflow.



🔑 Key features
- 🕒 Time-aware cross-validation that preserves chronological order
- 🔧 Extensive feature engineering: date features, aggregated customer/product features, lag/rolling metrics
- 🤖 Model families compared: Random Forest, LightGBM, XGBoost, CatBoost, Ridge Regression, Neural Networks
- 🔁 Reproducible pipelines: scikit-learn ColumnTransformer / Pipeline patterns
- 🔍 Explainability: guidance for SHAP and experiment tracking (MLflow / Weights & Biases)

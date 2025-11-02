# 🏠 House Price Prediction using Gradient Boosting and Linear Regression

This project aims to accurately predict residential house prices using **Machine Learning regression models**, primarily focusing on **Gradient Boosting Regressor** and **Linear Regression**.  
It enhances the approach presented in the reference research paper by introducing **advanced preprocessing**, **cross-validation**, and **hyperparameter tuning** for improved performance and real-world reliability.

---

## 📘 Overview

The model estimates property sale prices based on multiple housing attributes such as:
- Location
- Number of bedrooms and bathrooms
- Square footage (area)
- Year built
- Readiness to move
- Environmental descriptors

By applying **Gradient Boosting**, the model effectively captures non-linear interactions between these features to deliver more accurate predictions.

---

## 🧠 Research Paper Reference

This implementation is inspired by the IEEE paper:  
**“House Price Prediction Using Gradient Boosting and Linear Regression” (ICSEIET 2023)**  
Authors: Utkarsh Gupta et al.

Our implementation improves on the baseline accuracy reported in the paper by introducing:
- Robust preprocessing pipelines
- Cross-validation for model reliability
- Systematic hyperparameter tuning
- Feature importance and interpretability analysis

---

## 🚀 Enhancements Over the Research Paper

| Feature | Research Paper | Our Implementation |
|----------|----------------|--------------------|
| Model | Linear Regression | Gradient Boosting Regressor |
| Data Split | 70/30 single split | 70/30 with 5-fold CV |
| Imputation | Mean strategy | Median + Mode strategy |
| Encoding | Manual | Automated ColumnTransformer + OneHotEncoder |
| Hyperparameter Tuning | Not done | GridSearchCV over 135 combinations |
| Evaluation Metric | Accuracy (misused) | R² Score, RMSE |
| Achieved R² | ~0.85 | **0.91** |
| Code Reproducibility | Limited | Full pipeline with reproducible preprocessing |

---

## 🧩 Project Structure


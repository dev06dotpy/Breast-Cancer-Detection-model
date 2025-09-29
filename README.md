# Breast Cancer Detection ML project

This repository contains an end-to-end machine learning workflow:  
- Data cleaning & preprocessing  
- Model training & evaluation  
- Hyperparameter tuning with [Optuna](https://optuna.org/)  
- Model explainability with [SHAP](https://github.com/shap/shap)  

---

## Dataset
The dataset used is [Breast Cancer Wisconsin (Diagnostic) Dataset 1995](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

---

## Contents
- `data_exploration.ipynb` → Preprocessing and cleaning steps  
- `models.ipynb` → Training/testing baseline models, Hyperparameter optimization experiments and SHAP explanations for best models 

---

## Features
- **Data cleaning**: handles missing values, transformations, feature selection  
- **Model testing**: compares multiple ML models (e.g., Decision Trees, XGBoost, etc.)  
- **Hyperparameter tuning**: automated optimization with Optuna  
- **Model explainability**: SHAP values to interpret predictions  

---

## Screemshots
[Shap Summary Plot](screenshots\XGBoostClassifer_Shap_values.png)
[XGB Classifier performance metrics](screenshots\XGBoostClassifier_performance_metrics.png)


## Requirements
Install dependencies:

```bash
pip install -r requirements.txt
```
---
### Author
Dev

---

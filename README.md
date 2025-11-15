# Housing--Price--Data
House Prices: Advanced Regression Techniques

🏡 **House Prices Prediction – Kaggle Competition**

Advanced Regression Techniques using Machine Learning

This repository contains my end-to-end solution for the Kaggle competition:
“House Prices: Advanced Regression Techniques.”

The objective is to build a model that predicts home sale prices using 79 housing features—ranging from building quality to location factors.

This project demonstrates practical skills in:

📌 Data cleaning & preprocessing

📌 Feature engineering

📌 Model building & optimization (Random Forest, XGBoost, LightGBM, CatBoost)

📌 Hyperparameter tuning with RandomizedSearchCV

📌 Prediction & Kaggle submission pipeline

📌 Exploratory data analysis (EDA) & visualization

📂 Project Structure

```text
│── data/
│   ├── train.csv
│   ├── test.csv
│
│── notebook/
│   ├── Housing Price Prediction.ipynb
│
│── submission/
│   ├── stacked_submission.csv
│
└── README.md
```


1. **Project Overview**

The goal is to build a highly predictive model for housing sales prices.
The dataset includes:

Numerical & categorical features

Missing values

Skewed distributions

Neighborhood-level differences

Mixed-quality inputs requiring transformations

To address these challenges, the project includes detailed preprocessing and model optimization steps.

2. **Data Cleaning & Preprocessing**

✔ Missing value handling

a. Categorical missing values → "None"

b. Numerical missing values → median imputation

c. LotFrontage gaps

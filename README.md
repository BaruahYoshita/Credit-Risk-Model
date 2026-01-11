# Credit Risk Modeling – End-to-End Machine Learning Project

## 1. Problem Statement
The objective of this project is to build and compare machine learning models to predict the probability that a loan applicant will default, using historical application and credit bureau data.

This is a binary classification problem with:
- Strong class imbalance, since default is a rare event
- High-dimensional tabular features
- Missing values
- Business need for both discrimination and probability calibration

The output is a calibrated probability of default that can support downstream decision-making such as credit approval, risk-based pricing, and portfolio risk monitoring.

## 2. Dataset
Source: Home Credit Default Risk dataset from Kaggle

Target variable:
- TARGET = 1 → Defaulter
- TARGET = 0 → Non defaulter

The dataset contains:
- Demographic information
- Income and employment features
- Credit history from external bureaus
- Loan and application characteristics

Key challenges:
- Missing values
- Categorical variables
- Severe class imbalance
- Potential data leakage across related tables

## 3. Modeling Approach
Models to be implemented and compared:
- Logistic Regression (interpretable baseline)
- Random Forest 
- XGBoost 

## 4. Evaluation Metrics
- ROC-AUC
- Precision–Recall AUC
- KS Statistic
- Probability calibration -- Brier score, calibration curve

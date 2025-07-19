# 🏦 Bank Customer Churn Prediction

This project uses a bank dataset to predict whether a customer will leave the bank (churn) based on their personal and account information.

## 📌 Problem Statement

Predict the Exited status of customers using classification techniques.  
Dataset contains demographic and account-related features.

## 🧠 Model Used

- Gradient Boosting Classifier (sklearn)
- Precision: 0.86
- Recall: 0.87
- F1-score: 0.86
- ROC-AUC: 0.86

## 🔍 EDA Highlights

- Customers from Germany show higher churn rates.
- Younger customers are more likely to churn.
- Fewer active members → higher churn probability.

## 📊 Feature Importance

Top important features:
1. Age
2. Number of Products
3. IsActiveMember
4. Balance

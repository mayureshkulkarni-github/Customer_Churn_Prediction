# 📉 Customer Churn Prediction

This project aims to predict whether a customer will churn (leave) or not based on various features in a telecom dataset. The raw dataset was sourced from Kaggle, and the project involves complete **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, **model training**, and **deployment-ready Flask API integration**.

## 🔍 Project Overview

Customer churn is a key metric in the telecom industry. By identifying customers who are likely to leave, companies can proactively take actions to retain them. This project uses machine learning models to classify customers as churn or non-churn.

## 🧠 Machine Learning Models Used

- ✅ **Decision Tree Classifier**
- ✅ **Random Forest Classifier**

Both models were trained and evaluated to compare performance.

## 📊 Dataset Summary

- 📁 Source: Kaggle (Telco Customer Churn Dataset)
- 📦 Rows: 7032
- 📈 Target: `Churn` (0 = No, 1 = Yes)
- 🔢 Features: Customer demographics, service subscription details, billing information, etc.

## ⚙️ Technologies & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Flask (for API integration)
- Pickle / Joblib (for model serialization)

## 📈 Model Evaluation

| Metric       | Decision Tree | Random Forest |
|--------------|----------------|----------------|
| Accuracy     | 79%            | 79%            |
| Precision    | 63%            | 68%            |
| Recall       | 50%            | 45%            |
| F1-Score     | 56%            | 54%            |

> 🔍 Note: Random Forest had slightly better precision, but both models performed similarly overall.




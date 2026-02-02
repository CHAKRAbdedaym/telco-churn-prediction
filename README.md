# 📊 Telco Customer Churn Prediction (Machine Learning Project)

## 📌 Project Overview
This project aims to predict customer churn for a telecom company using Machine Learning techniques.  
Customer churn prediction helps businesses identify customers who are likely to leave and take proactive retention actions.

The project follows an **end-to-end ML pipeline**, from data preprocessing to model tuning and explainability.

---

## 🎯 Objectives
- Analyze customer behavior data
- Build and compare multiple ML models
- Handle class imbalance using SMOTE
- Optimize the best model with hyperparameter tuning
- Explain model predictions using SHAP
- Deliver a production-ready ML model

---

## 📂 Dataset
- Source: **Kaggle – Telco Customer Churn Dataset**
- Records: **7,032 customers**
- Features: **23 original features**
- Target variable: **Churn (0 = No, 1 = Yes)**

---

## 🛠️ Technologies & Tools
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- CatBoost, XGBoost, LightGBM
- Imbalanced-learn (SMOTE)
- SHAP (Explainable AI)
- Joblib
- Git & GitHub

---

## 🔄 Project Pipeline
1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature engineering
4. Train-test split
5. Class imbalance handling (SMOTE)
6. Model training and comparison
7. Hyperparameter tuning (CatBoost)
8. Model explainability with SHAP
9. Model saving for deployment

---

## 🤖 Models Evaluated
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- **CatBoost (Final Model)**

---

## 🏆 Final Model Performance (CatBoost – Tuned)

| Metric | Score |
|------|------|
| Accuracy | ~0.76 |
| F1 Score | ~0.60 |
| Recall (Churn) | ~0.69 |
| ROC-AUC | ~0.83 |

✔ High recall ensures most churners are detected  
✔ Strong ROC-AUC indicates good class separation  

---

## 🔍 Explainability (SHAP Insights)
Top features influencing churn:
- Customer tenure
- Internet service (Fiber optic)
- Payment method (Electronic check)

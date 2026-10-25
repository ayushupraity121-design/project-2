# Customer Churn Prediction & Retention Analysis

## 📌 Project Overview
This project develops a complete machine learning system to predict customer churn for a subscription-based telecom service. Beyond binary classification, it analyzes key drivers behind customer churn and provides actionable retention strategies.

## 🎯 Objectives
- Perform end-to-end data preprocessing and categorical feature encoding.
- Build and evaluate multiple classification models (**Logistic Regression**, **Decision Tree**, and **Random Forest**).
- Handle class imbalance and evaluate performance using **Confusion Matrix**, **ROC-AUC**, and **Classification Reports**.
- Identify critical drivers of customer churn using feature importance analysis.
- Provide practical retention recommendations and a deployed Streamlit web dashboard.

---

## 🛠️ Tools & Technologies Used
- **Python 3.10+**
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** VS Code, Jupyter Notebook
- **Deployment:** Streamlit

---

## 📂 Project Structure
```text
customer-churn-prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv   # IBM Telco Churn Dataset
│
├── notebooks/
│   └── churn_analysis.ipynb                   # Exploratory Data Analysis & Model Building
│
├── app.py                                     # Streamlit Web Application
├── churn_analysis.py                          # Full Pipeline Python Script
├── requirements.txt                           # Project Dependencies
└── README.md                                  # Project Documentation
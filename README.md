# Telecom Customer Churn Analysis

## 📌 Project Overview
Customer churn is a critical challenge in the telecommunications industry, directly impacting revenue and long-term growth. This project performs an end-to-end predictive analytics workflow to analyze customer behavior, identify key churn drivers, and build a machine learning model to support data-driven retention strategies.

---

## 🎯 Objectives
- Analyze customer demographics, service usage, and contract details
- Identify factors contributing to customer churn
- Build a predictive model to classify churn risk
- Translate analytical insights into actionable business recommendations

---

## 📂 Dataset
- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Records:** 7,043 customers
- **Target Variable:** Churn (Yes / No)
- **Data Quality:** No missing values

**Key Features:**
- Demographics (e.g., gender)
- Service subscriptions (internet, streaming, security, tech support)
- Contract type and tenure
- Payment methods and monthly charges

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Statistics:** SciPy  

---

## 🔍 Key Findings
- Month-to-month contracts show the highest churn rate (~43%)
- Fiber optic internet users exhibit higher churn compared to other service types
- Customers without online security or technical support churn more frequently
- Customer tenure is the strongest predictor of churn

---

## 🤖 Predictive Modeling
- **Model Used:** Logistic Regression
- **Overall Accuracy:** ~80%
- Strong performance in identifying non-churn customers
- Model insights support targeted retention strategies

---

## 📈 Business Recommendations
- Incentivize long-term contracts to reduce churn
- Improve technical support and online security services
- Focus retention efforts on early-tenure customers
- Use predictive insights to personalize customer engagement

---

## 📁 Repository Structure
telecom-churn-analysis/
├── Chun.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── requirements.txt
└── README.md


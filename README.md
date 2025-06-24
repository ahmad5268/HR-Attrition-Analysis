# 🧠 HR Attrition Analysis & Prediction

This project analyzes employee attrition using real-world HR data from IBM and builds a machine learning model to predict which employees are likely to leave.

---

## 📁 Dataset

- **Name**: WA_Fn-UseC_-HR-Employee-Attrition.csv  
- **Source**: [Kaggle - IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 🎯 Project Objectives

- Identify factors leading to employee attrition
- Explore salary, department, satisfaction, and performance trends
- Train and evaluate machine learning models to predict attrition
- Provide actionable insights for HR to reduce turnover

---

## 📊 Exploratory Data Analysis

The project includes:
- Correlation heatmaps
- Department-wise attrition plots
- Income and satisfaction distribution visualizations
- Salary binning and flag columns

---

## 🧹 Preprocessing

- Label encoding and one-hot encoding
- Dropping irrelevant or constant columns
- Binning income levels
- Creating target variable (`Attrition_Flag`)

---

## 🧠 Machine Learning

Two models were trained and evaluated:

| Model               | Accuracy | Notes |
|--------------------|----------|-------|
| Logistic Regression| ~87%     | Simple, interpretable |
| Random Forest       | ~85%     | Better performance, handles categorical features |

Metrics used:
- Confusion Matrix
- Precision, Recall, F1-Score

---

## 📌 Technologies Used

- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn

---

## 📈 How to Run This Project

1. Clone this repo:
```bash
git clone https://github.com/yourusername/HR-Attrition-Analysis.git
cd HR-Attrition-Analysis

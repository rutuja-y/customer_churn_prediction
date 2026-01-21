# Customer Churn Prediction

## 📌 Overview

This project predicts **customer churn** for a banking dataset using machine learning. The goal is to identify customers who are likely to leave the bank so that retention actions can be taken in advance.

---

## 🎯 Objective

Build a classification model to predict whether a customer will **churn (Exited = 1)** or **stay (Exited = 0)**.

---

## 📊 Dataset

* **File:** Churn_Modelling.csv
* **Target Variable:** Exited
* **Features:** Customer demographics, account details, and activity information

---

## 🔍 Key Steps

* Performed data cleaning and exploratory data analysis (EDA)
* Identified class imbalance in the target variable
* Created meaningful features such as credit utilization and interaction score
* Encoded categorical variables and scaled numerical features
* Applied SMOTE and class-weighted models to handle imbalance

---

## 🤖 Models Used

* Logistic Regression
* Random Forest
* K-Nearest Neighbors
* Support Vector Machine
* Gradient Boosting
* XGBoost

---

## 📈 Model Evaluation

* Recall
* F1-Score
* ROC-AUC

---

## 🏆 Best Model

**Gradient Boosting** performed best, achieving the highest F1-score and ROC-AUC, making it most effective for churn prediction.

---

## 🧰 Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, Imbalanced-learn

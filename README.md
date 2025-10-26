# 💳 Credit Card Fraud Detection using Machine Learning

This project demonstrates how **machine learning techniques** can be applied to detect fraudulent credit card transactions.
By analyzing transaction data and building predictive models, it aims to differentiate between **legitimate** and **fraudulent** activities with high accuracy.

---

## 🚀 Project Overview

Credit card fraud is a growing issue for financial institutions worldwide.
This project focuses on building a **fraud detection model** using Python and machine learning algorithms.
The workflow includes **data preprocessing, visualization, handling class imbalance**, and **training multiple models** to predict fraud effectively.

---

## 🧠 Objectives

* Analyze and visualize transaction data
* Handle **imbalanced datasets** using oversampling (SMOTE)
* Train and compare different **machine learning models**
* Evaluate model performance using **ROC-AUC**, **F1-score**, and **confusion matrix**

---

## 📂 Dataset Summary

* **Dataset Name:** `creditcard.csv`
* **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* **Total Rows:** 284,807
* **Total Columns:** 31
* **First 10 Columns:** `Time`, `V1`, `V2`, `V3`, `V4`, `V5`, `V6`, `V7`, `V8`, `V9`
* **Non-Fraud Cases:** 284,315
* **Fraud Cases:** 492
* **Fraud Percentage:** ≈ 0.17%

The dataset contains transactions made by European cardholders in September 2013.
All numerical input variables (except `Time` and `Amount`) have been transformed using **Principal Component Analysis (PCA)** for confidentiality.

---

## 🧰 Technologies Used

* **Python 3.x**
* **NumPy** – numerical operations
* **Pandas** – data manipulation
* **Matplotlib & Seaborn** – data visualization
* **Scikit-learn** – model training and evaluation
* **Imbalanced-learn (SMOTE)** – handle class imbalance

---

## 📊 Model Evaluation Metrics

| Metric        | Description                          |
| ------------- | ------------------------------------ |
| **Accuracy**  | Overall correctness of predictions   |
| **Precision** | Ability to avoid false positives     |
| **Recall**    | Ability to detect actual frauds      |
| **F1-Score**  | Balance between precision and recall |
| **ROC-AUC**   | Measures class separability          |

---

## 📈 Results Summary

* The model successfully detects fraudulent transactions with high precision and recall.
* **Random Forest** and **Logistic Regression** performed best for balanced performance.
* **SMOTE** improved fraud detection rates by balancing minority classes.

---

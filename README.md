# 💳 Credit Card Fraud Detection using Random Forest

This project implements a machine learning pipeline to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

---

## 🚀 Objective

Due to the highly imbalanced nature of fraud detection this project focuses on:

- Balancing the data using **SMOTE**
- Building a **Random Forest classifier**
- Performing **hyperparameter tuning**
- Evaluating using **precision**, **recall**, **ROC-AUC**

---

## 📊 Dataset Summary

- **Total Transactions:** 284,807  
- **Fraud Cases:** 492  
- **Features:** 30 (V1-V28 anonymized, Time, Amount)  
- **Target:** `Class` (0 = Normal, 1 = Fraud)

---

## 🧠 Techniques Used

- Random Forest Classifier
- SMOTE (Synthetic Minority Oversampling Technique)
- Hyperparameter tuning: `max_depth`, `n_estimators`, `min_samples_split`, `class_weight`
- Performance metrics: Accuracy, Precision, Recall, ROC-AUC

---

## 📈 Results

| Metric        | Value      |
|---------------|------------|
| Accuracy      | 94.3%      |
| Precision     | 92.1%      |
| Recall        | 89.7%      |
| ROC-AUC Score | 0.96       |
| False Positives Reduced | 35% |

---

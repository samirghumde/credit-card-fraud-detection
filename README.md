# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
Credit card fraud detection is a critical problem in financial security due to the rapid growth of digital transactions. Fraudulent transactions represent only a small fraction of total transactions, making the dataset highly imbalanced. Traditional machine learning models often struggle to correctly identify fraud cases.

This project proposes an **Imbalance-Aware Machine Learning Framework** that applies **SMOTE (Synthetic Minority Over-sampling Technique)** along with optimized classification models to improve fraud detection performance.

---

## 🎯 Objectives
- Analyze the impact of **class imbalance**
- Train **baseline ML models**
- Apply **SMOTE for imbalance handling**
- Build an improved **Random Forest + SMOTE model**
- Compare performance using evaluation metrics

---

## 📊 Dataset
- **Name:** Credit Card Fraud Detection Dataset
- **Source:** Kaggle
- **Records:** 284,807 transactions
- **Fraud Cases:** 492
- **Features:** 30 numerical features + Class label

---

## 🧠 Machine Learning Models Used

### ✅ Baseline Models
- Logistic Regression
- Random Forest

### 🚀 Proposed Model
- Random Forest with **SMOTE balancing**

---

## ⚙️ Methodology
1. Data preprocessing & feature scaling  
2. Train-test split (80:20)  
3. Baseline model training  
4. Class imbalance handling using **SMOTE**  
5. Proposed model training  
6. Performance evaluation  

---

## 📈 Evaluation Metrics
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

---

## 🏆 Results Summary

| Model | ROC-AUC |
|-------|---------|
| Logistic Regression | 0.816 |
| Random Forest | 0.908 |
| **Random Forest + SMOTE** | **0.913** |

The proposed model achieved improved fraud detection performance, particularly in **recall and ROC-AUC**, confirming the importance of imbalance handling.

---

## 📷 Sample Outputs

### 🔹 Class Imbalance
Shows severe imbalance between legitimate and fraud transactions.

### 🔹 Confusion Matrix
Visualizes classification accuracy of the proposed model.

### 🔹 ROC-AUC Comparison
Demonstrates improvement of the SMOTE-based model.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1️⃣ Clone repository  
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git

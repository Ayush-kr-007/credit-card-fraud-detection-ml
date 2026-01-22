# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using
machine learning techniques. The dataset is highly imbalanced, making accuracy
an unreliable metric. The goal is to maximize fraud detection while minimizing
false negatives.

## 🧠 Problem Statement
Credit card fraud is a real-world imbalanced classification problem where
fraudulent transactions are extremely rare. Missing fraudulent cases can lead
to significant financial losses.

## 📊 Dataset
- Source: Kaggle Credit Card Fraud Dataset
- Features: Anonymized transaction features (V1–V28)
- `Amount`: Transaction amount
- `Class` (target):
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction

⚠️ Note: Dataset is not included in this repository due to size limitations.
Please download it from Kaggle and place it in the `data/` directory.

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn

## 🔄 Machine Learning Workflow
1. Data loading and cleaning
2. Duplicate removal
3. Feature engineering (log transformation)
4. Stratified train-test split
5. Handling class imbalance:
   - Class weighting
   - SMOTE oversampling
6. Model evaluation using:
   - Precision
   - Recall
   - F1-score
   - ROC-AUC
   - Precision-Recall AUC
7. Threshold tuning

## 🤖 Models Used
- Logistic Regression (baseline)
- Logistic Regression with class weighting
- Logistic Regression with SMOTE

## 📈 Key Results
- Class imbalance significantly affected model performance
- Class weighting and SMOTE improved recall
- Precision–Recall AUC proved more informative than accuracy
- Threshold tuning improved fraud detection sensitivity

## Dataset not included due to GitHub file size limits.
Download from Kaggle and place creditcard.csv in the project directory.
## ✅ Conclusion
This project demonstrates real-world handling of imbalanced datasets,
appropriate metric selection, and threshold optimization for fraud detection
systems.

---

⭐ If you find this project useful, feel free to star the repository!


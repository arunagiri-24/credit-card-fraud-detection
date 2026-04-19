📊 Credit Card Fraud Detection
📌 Overview

This project detects fraudulent credit card transactions using machine learning and deep learning on a highly imbalanced dataset.

📂 Dataset
Source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Transactions: 284,807
Fraud cases: 492 (0.172%)
Features: V1–V28 (PCA), Time, Amount
Target: Class (0 = Legit, 1 = Fraud)
⚙️ Methods
Models: LightGBM, XGBoost, CatBoost, Neural Network
Handling imbalance: Class weight tuning
Optimization: Bayesian optimization
Ensemble: Soft voting
Improvement: Threshold optimization
📈 Metrics
Precision, Recall, F1-score
ROC-AUC
MCC
📊 Results (Best)
Precision: 0.8265
Recall: 0.8265
F1-score: 0.8265
ROC-AUC: 0.9711
MCC: 0.8262

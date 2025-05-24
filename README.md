# Fraud_detection
# 💳 Fraud Detection Using Machine Learning

This project focuses on detecting fraudulent transactions using machine learning techniques. The entire workflow — including data exploration, preprocessing, model training, and evaluation — was completed in Google Colab using Python libraries like Pandas, Scikit-learn, and Matplotlib.

## 🧾 Overview

Financial fraud, especially involving credit cards, is a growing concern. This project uses supervised machine learning to classify transactions as fraudulent or legitimate. The primary goal is to build a reliable model that can detect fraud with high precision and recall.

## ✅ Features

- Data Cleaning & Preprocessing
- Handling Imbalanced Dataset using SMOTE
- Model Training (Logistic Regression, Random Forest, etc.)
- Evaluation using Precision, Recall, F1-Score, and ROC-AUC
- Data Visualization (Class distribution, Correlation matrix, etc.)

## 📊 Dataset

- **Name**: Credit Card Fraud Detection
- **Source**: [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions with 492 fraud cases
- **Note**: Features are anonymized using PCA for confidentiality.

## 🧠 Approach

1. **Exploratory Data Analysis (EDA)** – Understand class distribution and feature correlations.
2. **Preprocessing** – Normalize and scale data, handle imbalance using SMOTE.
3. **Model Training** – Train multiple models (e.g., Logistic Regression, Random Forest).
4. **Evaluation** – Compare models based on performance metrics like:
   - Precision
   - Recall
   - F1-Score
   - ROC Curve

## 📈 Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 97.5%   | 89%       | 81%    | 85%      |
| Random Forest       | 99.2%   | 95%       | 91%    | 93%

> Note: The Random Forest model provided the best performance in terms of both recall and precision.

## 🧰 Technologies Used

- Google Colab
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- imbalanced-learn (for SMOTE)

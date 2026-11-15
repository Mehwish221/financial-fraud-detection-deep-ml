# Advanced Deep ML-Driven Fraud Detection System

## 📌 Project Overview
This repository contains an end-to-end Advanced Deep Learning and Machine Learning pipeline designed to detect fraudulent financial transactions. Completed as part of the **Fundamentals of Machine Learning (FML)** course, this project tackles the extreme class imbalance problem (only 3.58% of transactions are fraudulent) using a massive dataset of 5,000,000 records. 

The project explores the limits of traditional ML (KNN, SVM) and compares them to advanced techniques like Gradient Boosting (XGBoost) and Deep Learning (LSTM).

## 📊 Dataset
*   **Source:** [Kaggle - Financial Transaction Fraud Detection](https://www.kaggle.com/code/nguyentatkien/financial-transaction-fraud-detection/input)
*   **Size:** 5,000,000 rows, 18 original columns
*   **Target Variable:** `is_fraud` (0 = Legitimate, 1 = Fraud)

## 🛠️ Methodology
*   **Feature Engineering:** Expanded from 16 to 39 features (Time, Amount, Network, and Fraud History).
*   **Class Balancing:** Random Downsampling, SMOTE (Training only), and Class Weights.
*   **Models:** KNN, XGBoost, SVM and LSTM.

## 🏆 Results
*   **XGBoost:** 97.99% Accuracy, 99.76% Recall.
*   **LSTM:** 97.97% Accuracy, 100% Recall.
*   **KNN:** 96.68% Accuracy, 98.18% Recall.
*   **SVM:** 87.82% Accuracy, 100% Recall.

## 👥 Contributors
*   Mehwish Roqaiya
*   Muneeba

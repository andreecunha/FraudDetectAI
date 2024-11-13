# FraudDetectAI: Machine Learning for Financial Fraud Detection

**FraudDetectAI** is a machine learning-based system designed to identify fraudulent transactions in financial datasets. This project implements a full pipeline for fraud detection, including data preprocessing, feature selection, and model evaluation, leveraging state-of-the-art algorithms and techniques.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [System Workflow](#system-workflow)
4. [Installation Guide](#installation-guide)

---

## Project Overview

Financial fraud has increased exponentially with the rise of electronic payment systems. **FraudDetectAI** aims to address this challenge by:
- Developing machine learning models to classify transactions as fraudulent or legitimate.
- Handling highly imbalanced datasets through oversampling techniques like SMOTE.
- Evaluating the effectiveness of different machine learning algorithms.

The system is trained and evaluated on the **Credit Card Fraud Detection Dataset** from Kaggle, which contains 284,807 transactions, only 0.172% of which are fraudulent.

---

## Key Features

1. **Data Preprocessing:**
   - Scaling and normalizing transaction data.
   - Addressing class imbalance using SMOTE (Synthetic Minority Oversampling Technique).

2. **Feature Engineering:**
   - Feature selection using Random Forest feature importance.
   - Focus on features such as transaction time, amount, and principal components.

3. **Machine Learning Models:**
   - Implemented models include:
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Neural Networks (NN)

4. **Evaluation Metrics:**
   - Precision
   - Recall
   - Accuracy (used cautiously due to data imbalance)

---

## System Workflow

1. **Data Loading:**
   - Load the Credit Card Fraud Detection Dataset.

2. **Data Preprocessing:**
   - Scale and normalize features.
   - Apply SMOTE to balance the dataset.

3. **Feature Selection:**
   - Use feature importance scores from Random Forest to select the top 10 features.

4. **Model Training and Evaluation:**
   - Train models using an 80:20 train-test split.
   - Evaluate models on metrics like recall and precision.

---

## Installation Guide

1. Clone the repository:
   ```bash
   git clone https://github.com/andreecunha/FraudDetectAI.git

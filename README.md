# Credit-Card-Fraud-Detection

## Overview
This project, titled "Balancing Efficacy and Efficiency: Identifying the Optimal Model for Credit Card Fraud Detection," investigates various machine learning and deep learning models to detect fraudulent transactions in credit card data. It utilizes a dataset from the Machine Learning Group at Université Libre de Bruxelles, covering 284,807 transactions.

## Objective
To develop a predictive model that efficiently and accurately identifies fraudulent credit card transactions, addressing the challenge of class imbalance in the dataset.

## Models Evaluated
- Logistic Regression
- K-Nearest Neighbors
- Naive Bayes
- SGDClassifier
- LightGBM
- Deep Learning Autoencoder

## Key Techniques
- Feature Engineering: Standardization of 'Time' and 'Amount' features.
- Class Imbalance Handling: Using SMOTE and majority random under-sampling.
- Performance Metrics: Accuracy, Precision, Recall, F2 Score, MCC, ROC AUC.

## Results
The LightGBM and SGDClassifier models showed optimal performance in fraud detection, balancing accuracy with computational efficiency.

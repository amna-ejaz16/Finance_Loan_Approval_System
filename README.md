# Finance Loan Approval System

## Overview

Built an end-to-end supervised machine learning project for predicting loan approval outcomes using **binary classification**.

The project applies **Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and feature scaling** to prepare the dataset for machine learning. Three classification algorithms — **Logistic Regression, K-Nearest Neighbors (KNN), and Naive Bayes** — are trained and compared.

Model performance is evaluated using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix** to assess and compare the classification results.

## Machine Learning Workflow

```text
Data
  ↓
EDA & Preprocessing
  ↓
Feature Engineering
  ↓
Train-Test Split
  ↓
Feature Scaling
  ↓
Model Training
  ↓
Model Evaluation
  ↓
Model Comparison
```

## Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Evaluation

The models are compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 88.0% | 78.5% | 83.6% | 81.0% |
| KNN | 78.5% | 67.3% | 57.4% | 61.9% |
| Naive Bayes | 86.0% | 81.1% | 70.5% | 75.4% |

Based on the evaluated metrics, **Logistic Regression achieved the best overall performance**, while **Naive Bayes achieved the highest Precision** among the three models.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

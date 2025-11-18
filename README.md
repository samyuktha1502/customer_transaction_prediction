# customer_transaction_prediction
📌 Project Overview

This project focuses on predicting whether a customer will make a transaction in the future based on their historical behavior patterns. The goal is to build a machine learning model that helps businesses improve targeted marketing, customer retention, and personalized engagement strategies.

This project was completed as part of the DataMites Data Science Internship (Capstone Project).

# Problem Statement

Companies often struggle to identify which customers are likely to perform a transaction again. Understanding this behavior helps businesses optimize marketing budgets and improve retention.

The objective is to:
✔ Analyze customer behavior
✔ Engineer meaningful features
✔ Handle imbalanced target variables
✔ Build a model to predict transaction likelihood
✔ Evaluate performance using appropriate metrics


#  Exploratory Data Analysis (EDA)

Key steps performed:

Checked null values, duplicates, and outliers

Analyzed customer demographics & spending behavior

Visualized distributions and correlations

Identified trends, purchase frequency, and recency patterns

Noted imbalance in the target variable (transaction vs no transaction)


# 🧩 Feature Engineering

Important features created:

RFM Metrics:

Recency (days since last transaction)

Frequency (no. of transactions)

Monetary (total spend)

Behavioral Features:

Rolling window aggregates

Time-based trends

Average transaction intervals

Activity flags

Derived Metrics:


# Modeling Approach

Algorithms used:

Logistic Regression

Random Forest

Gradient Boosting

XGBoost (Best performing model)

Customer stability score

Seasonality indicators

**Hyperparameter Tuning:

GridSearchCV

RandomizedSearchCV

# 📈 Evaluation Metrics

To measure performance:

Accuracy

ROC-AUC (Primary metric)

Precision, Recall, F1-Score

Confusion Matrix

PR Curve

XGBoost achieved the strongest performance with the highest ROC-AUC.

# 🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

Jupyter Notebook

Transaction probability features

Feature engineering significantly improved model performance.

**Machine Learning in Finance – Fraud Detection Project**

This project was developed during my Erasmus exchange semester at the University of Warsaw as part of the Machine Learning in Finance coursework.

📌 Project Overview

Financial fraud leads to significant losses for banks and financial institutions worldwide. The objective of this project is to build and evaluate machine learning models capable of detecting fraudulent financial transactions.

The task is formulated as a binary classification problem:

0 — Legitimate transaction

1 — Fraudulent transaction

Due to the highly imbalanced nature of fraud data, special attention is given to evaluation metrics beyond simple accuracy.

🎯 Objectives

Build multiple machine learning models for fraud detection

Handle imbalanced transaction data appropriately

Compare model performance using relevant evaluation metrics

Identify the most effective approach for detecting fraudulent transactions

📊 Dataset Description

**The dataset contains transaction-level financial data, including:**

Transaction amounts

Customer-related attributes

Behavioral transaction features

Binary target variable indicating fraud

The dataset is highly imbalanced, reflecting real-world financial systems where fraudulent transactions represent only a small fraction of total activity.

⚙️ Methodology

**The project follows a structured machine learning pipeline:**

Data preprocessing

Handling missing values

Feature encoding

Scaling (where required)

Train-test split

Model training

Model evaluation

Performance comparison

🤖 Models Implemented

**The following models were trained and evaluated:**

Logistic Regression – baseline interpretable model

K-Nearest Neighbors (KNN) – distance-based method

Random Forest – ensemble tree-based model

XGBoost – gradient boosting algorithm

📈 Evaluation Metrics

**Given the class imbalance, models were evaluated using metrics such as:**

Precision

Recall

F1-score

ROC-AUC

Special emphasis was placed on detecting fraudulent transactions effectively while minimizing false positives.

🛠 Tech Stack

Python

Jupyter Notebook

pandas

numpy

scikit-learn

xgboost

matplotlib / seaborn


Author

Jan Dzemiashkevich
Erasmus Exchange Student
Machine Learning in Finance

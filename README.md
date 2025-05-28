# credit_card-fraud-detection

This project aims to build a machine learning model that detects fraudulent credit card transactions based on anonymized features. Fraudulent activities can cause huge financial losses to banks and inconvenience to customers — early detection is crucial.



# Dataset
Source: Kaggle - Credit Card Fraud Detection

Transactions made by European cardholders in September 2013.

The dataset contains 284,807 transactions over two days.

Includes 492 frauds, making it highly imbalanced (fraud = 0.172%).

# Features
All features (except Time and Amount) are PCA-transformed for privacy.

The target variable Class indicates fraud (1) or genuine (0).

# Model Workflow
The notebooks (Credit Card Fraud Detection.ipynb and Model_Final.ipynb) cover:

Data preprocessing and handling imbalanced data

Exploratory Data Analysis (EDA)

Feature scaling and outlier detection

Training multiple classification models

Model evaluation using precision, recall, F1-score, ROC-AUC

Final model selection and prediction

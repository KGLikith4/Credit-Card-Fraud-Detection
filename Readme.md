# Credit Card Fraud Detection

Description
The Credit Card Fraud Detection project aims to build a machine learning model that detects fraudulent credit card transactions. The project focuses on using supervised learning algorithms to classify transactions as either legitimate or fraudulent. The dataset used in this project contains a large number of transactions and is highly imbalanced, meaning most transactions are legitimate, and only a small percentage are fraudulent.



## Project Overview

This project builds a machine learning model to detect fraudulent credit card transactions. The goal is to predict whether a transaction is fraudulent based on various features like the transaction amount, user ID, and other anonymized data. The dataset used is from Kaggle and contains over 280,000 transactions, with a small percentage of fraudulent ones.

## Technologies Used

- Python
- Pandas, Scikit-Learn, XGBoost
- Matplotlib, Seaborn for visualization
- Flask/FastAPI for model deployment

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection

Steps Involved
Data Collection:

Download or access a publicly available dataset (e.g., from Kaggle’s Credit Card Fraud Detection).

Data Preprocessing:

Handle missing values.

Perform feature scaling or normalization.

Apply techniques to address class imbalance (e.g., oversampling/undersampling).

Model Building:

Split the data into training and testing sets.

Train several models, such as Logistic Regression, Decision Trees, Random Forest, or Neural Networks.

Model Evaluation:

Evaluate the models using appropriate metrics, particularly focusing on recall and precision, as fraud detection requires minimizing false negatives (missed fraud cases).

Hyperparameter Tuning:

Use GridSearchCV or RandomizedSearchCV to find the best hyperparameters for the models.

Deployment:

Create a REST API to make predictions on new, incoming transactions using a framework like Flask or FastAPI.



Evaluation Metrics
Precision: 0.98

Recall: 0.95

F1-Score: 0.96

AUC: 0.99

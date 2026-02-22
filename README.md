🌧️ Rainfall Prediction using Machine Learning
📌 Project Overview

This project builds an end-to-end machine learning pipeline to predict whether it will rain tomorrow using historical weather data from Melbourne, Australia. The workflow includes preprocessing, feature engineering, model comparison, hyperparameter tuning, and evaluation.

🔍 Key Steps Implemented

Data cleaning and preprocessing

Feature engineering (Season extraction from Date)

Automatic detection of numerical and categorical features

ColumnTransformer for scaling and one-hot encoding

Random Forest & Logistic Regression models

Hyperparameter tuning using GridSearchCV with StratifiedKFold

Model evaluation using Accuracy, Recall (True Positive Rate), Confusion Matrix

📊 Results

Random Forest Accuracy: ~83%

True Positive Rate (Rain detection): ~48%

Logistic Regression improved recall when using class balancing

🔎 Key Insight:
Accuracy alone is misleading in imbalanced datasets. Recall (True Positive Rate) is critical when predicting rainfall events.

🛠️ Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

Jupyter Notebook

📈 Learning Outcomes

Building production-style ML pipelines

Handling imbalanced datasets

Model comparison & hyperparameter tuning

Interpreting feature importance

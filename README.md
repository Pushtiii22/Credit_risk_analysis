# Credit_risk_analysis
📌 Overview

This project aims to assess credit risk by using supervised machine learning techniques to classify loan applicants as low or high risk. The dataset contains features such as loan amount, interest rate, annual income, and loan grade, which are used to train and evaluate various models.

🎯 Objectives

Analyze the characteristics of borrowers and loans

Preprocess the data (handle categorical variables, scale features, etc.)

Train and evaluate classification models

Use imbalanced-learn techniques to address class imbalance

Compare model performance using metrics like precision, recall, and F1-score

🗃️ Dataset

Source: Lending Club loan data (via lending_data.csv)

Size: ~75,000 records

Key Features: loan_status, loan_amount, interest_rate, annual_income, dti, grade, home_ownership, etc.

Target Variable: loan_status (Fully Paid / Charged Off)

🛠️ Tools & Technologies

Python 3.x

Pandas, NumPy

Scikit-learn

Imbalanced-learn

Matplotlib, Seaborn

Jupyter Notebook

⚙️ Machine Learning Models

The following models were implemented and evaluated:

Logistic Regression (with resampling methods like SMOTE and RandomOverSampler)

Ensemble methods (BalancedRandomForestClassifier, EasyEnsembleClassifier)

Resampling Techniques:
SMOTE: Synthetic Minority Oversampling Technique

RandomOverSampler

Balanced Random Forest

Easy Ensemble AdaBoost

📊 Model Evaluation

Used confusion matrix and classification report (precision, recall, f1-score)

Focused on improving recall due to the cost of false negatives in credit risk


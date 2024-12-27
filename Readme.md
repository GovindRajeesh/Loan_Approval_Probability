# Loan Approval Prediction

This repository contains a Jupyter Notebook that implements a machine learning solution to predict loan approvals. The notebook was developed as part of a Kaggle competition aimed at analyzing financial and demographic data to predict the likelihood of loan approval. 

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [How to Use](#how-to-use)
- [Future Improvements](#future-improvements)

## Overview
Loan approval is a critical task for financial institutions, ensuring that loans are provided to eligible applicants while minimizing risks. The goal of this project is to predict whether a loan application will be approved based on features such as income, credit history, and loan amount.

The solution uses various data preprocessing techniques, exploratory data analysis (EDA), feature engineering, and machine learning models to achieve high prediction accuracy.

---

## Dataset
The dataset provided by the Kaggle competition includes:
- **Train.csv**: Data with labels for training the model.
- **Test.csv**: Unlabeled data for making predictions.
- **SampleSubmission.csv**: Template for submission format.

### Features
- **Applicant Income, Co-applicant Income**: Financial details of the applicant and co-applicant.
- **Loan Amount, Loan Term**: Loan details.
- **Credit History**: Creditworthiness of the applicant.
- **Gender, Married, Dependents, Education**: Demographic information.

### Target
- **Loan_Status**: Binary label indicating whether a loan was approved (1) or not (0).

---

## Approach

1. **Data Preprocessing**:
   - Encoding categorical variables.

2. **Feature Engineering**:
   - Using pca to handdle loan intent

3. **Model Training**:
   - Models used include Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
   - Hyperparameter tuning with GridSearchCV and cross-validation.

4. **Evaluation**:
   - Cross validation

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Pandas, NumPy for data manipulation.
  - Matplotlib, Seaborn for visualization.
  - Scikit-learn for machine learning.
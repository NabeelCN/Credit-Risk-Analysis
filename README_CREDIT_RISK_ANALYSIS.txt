# Credit Risk Analysis - Loan Status Prediction

## Project Overview

This project focuses on analyzing credit risk and predicting loan approval status using Machine Learning techniques. Financial institutions can use this model to assess the likelihood of loan repayment and make informed lending decisions.

The dataset contains borrower information such as income, employment length, loan amount, interest rate, home ownership status, credit history, and previous default records.

---

## Problem Statement

Predict whether a loan applicant is likely to default or successfully repay a loan based on their financial and personal attributes.

Target Variable:
- `loan_status`

---

## Dataset Information

Dataset Features:

| Feature | Description |
|----------|-------------|
| person_age | Applicant age |
| person_income | Annual income |
| person_home_ownership | Home ownership status |
| person_emp_length | Employment length |
| loan_intent | Purpose of loan |
| loan_grade | Loan grade assigned |
| loan_amnt | Loan amount |
| loan_int_rate | Loan interest rate |
| loan_percent_income | Loan amount as percentage of income |
| cb_person_default_on_file | Previous default history |
| cb_person_cred_hist_length | Credit history length |
| loan_status | Loan repayment status (Target) |

Dataset Size:
- Rows: 32,581
- Columns: 12

---

## Project Workflow

### 1. Data Collection
- Load dataset using Pandas.

### 2. Data Preprocessing
- Handle missing values.
- Encode categorical variables.
- Feature scaling if required.

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis.
- Correlation analysis.
- Loan risk pattern identification.

### 4. Model Building
Common algorithms used:
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- XGBoost (optional)

### 5. Model Evaluation
Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

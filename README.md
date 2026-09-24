# Loan Approval Prediction

## Project Objective

This project predicts whether a loan application will be approved based on borrower information.

## Dataset

The dataset contains information about:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

Target variable:

- Y = Loan Approved
- N = Loan Not Approved

## Machine Learning Models

The following models were compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest

## Preprocessing

The project handles:

- Missing values
- Categorical variables
- Numerical scaling
- Class imbalance

## Evaluation Metrics

Models were evaluated using:

- Precision
- Recall
- F1 Score
- ROC-AUC

## Final Model

Random Forest was selected for the final demonstration based on validation performance.

An example threshold of 0.35 was used after validation-based threshold analysis.

## Files

- `loan_prediction.csv` - Dataset
- `loan_approval_prediction.ipynb` - Machine learning notebook
- `loan_approval_short_report.docx` - Project report

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
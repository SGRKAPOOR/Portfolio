# Loan Default Prediction

This project focuses on predicting loan default using machine learning techniques. It utilizes a dataset containing various features related to loan applicants such as loan amount, interest rate, employment length, home ownership status, annual income, and more. The goal is to build a predictive model that can accurately classify whether a loan applicant is likely to default or not.

## Dataset

The dataset used in this project is stored in a CSV file named `loan_working_ML.csv`. It contains the following columns:

1. Loan_Amt: Loan amount requested by the applicant.
2. Int_Rate: Interest rate on the loan.
3. Sub_Grade_M: Sub-grade of the loan.
4. Emp_Length: Employment length of the applicant.
5. Home_Ownership: Status of home ownership.
6. Annual_Inc: Annual income of the applicant.
7. Verification_Status: Verification status of the applicant's income.
8. Total_Dti: Debt-to-income ratio of the applicant.
9. Delinq_2Yrs: Number of delinquencies in the past 2 years.
10. Mort_Acc: Number of mortgage accounts.
11. Pub_Rec_Bankruptcies: Number of public record bankruptcies.
12. Credit_Limit: Credit limit of the applicant.
13. Total_Bal_Ex_Mort: Total balance excluding mortgage.
14. Loan_Status: Target variable indicating loan status (0: non-default, 1: default).

## Preprocessing

The preprocessing steps include:

- Handling missing values: Null values in the `Emp_Length` and `Total_Dti` columns were replaced with their respective means.
- Feature encoding: Categorical variables such as `Sub_Grade_M`, `Home_Ownership`, and `Verification_Status` were label encoded.
- Outlier removal: Outliers in numerical columns were removed using Z-score method.
- Train-test split: The data was split into 80% training set and 20% test set.

## Model Building

Two machine learning models were trained and evaluated:

1. Decision Tree Classifier: A decision tree classifier was trained with hyperparameters tuned using GridSearchCV.
2. Random Forest Classifier: A random forest classifier was trained with hyperparameters tuned using GridSearchCV.

## Evaluation

The models were evaluated based on the following metrics:

- Accuracy Score
- F1 Score
- Precision
- Recall
- Log Loss
- Confusion Matrix
- ROC Curve

## Feature Importance

Feature importance was analyzed using both Decision Tree and SHAP (SHapley Additive exPlanations) models.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, shap

## Usage

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to train and evaluate the models.

## Author

Sagar Kapoor


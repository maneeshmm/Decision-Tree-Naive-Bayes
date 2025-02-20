# Project Report: Loan Eligibility Prediction

## 1. Introduction
This project aims to predict loan eligibility based on applicant details such as income, credit history, and loan amount. The dataset was preprocessed and analyzed before training classification models to determine loan approval status.

## 2. Data Preprocessing

Loaded the dataset and checked for missing values, duplicates, and inconsistencies.

Handled missing values using mode for categorical columns and mean/median for numerical ones.

Applied feature engineering, including log transformation for skewed numerical variables like LoanAmount.

Encoded categorical variables to numerical values for model compatibility.

## 3. Exploratory Data Analysis (EDA)

Performed statistical analysis and visualized data distributions using histograms, box plots, and count plots.

Identified key patterns, such as the impact of Credit_History on Loan_Status.

Explored correlations between variables and their influence on loan approval.

## 4. Model Implementation

Used Decision Tree and Naive Bayes classifiers for loan eligibility prediction.

Split the dataset into training and testing sets for model evaluation.

Trained both models and compared their performance metrics.

## 5. Model Evaluation

Evaluated models based on accuracy, precision, recall, and F1-score.

Decision Tree provided high interpretability but may have overfitted the data.

Naïve Bayes performed well with categorical features but had limitations with numerical attributes.

## 6. Conclusion

Decision Tree is suitable for interpretability but may be prone to overfitting.

Naive Bayes is useful for categorical data but has limitations with numerical attributes.

This project successfully demonstrates loan eligibility prediction using machine learning techniques, with insights gained from EDA and model evaluations guiding future enhancements.

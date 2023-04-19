#Delinquency-Telecom-Model
This repository contains code for developing a delinquency model that predicts, in terms of a probability for each loan transaction, whether the customer will be paying back the loaned amount within 5 days of insurance of loan (Label ‘1’ & ’0’).

#Dataset
The dataset used is taken from Kaggle website.
The dataset consists of 37 features that includes customer ID, age on network, loan amount, payback history, etc. Exploratory Data Analysis is performed using matplotlib, seaborn libraries, and statistical analysis to find out missing values, outliers, and feature selection.

#Machine Learning Models
Machine Learning Models including Logistic Regression, Naive Bayes algorithm are used for predicting the output. The dataset used is imbalanced hence SMOTE algorithm is used for generating synthetic data using interpolation to overcome the problem of an imbalanced dataset.

#Results
The delinquency model achieved an accuracy score of 85.7% on the test data.

#Contributors
Gaurav Bhatia

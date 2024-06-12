## Overview of the Analysis

Purpose:  
The objective of this analysis is to develop machine learning models to predict loan status based on financial information provided in the dataset.

Financial Information:  
The dataset includes the following features: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.

Variable Information:  
The target variable being predicted is the loan status, which consists of 18,759 healthy loans and 625 high-risk loans.

Machine Learning Process:  
Data Preprocessing- Load the dataset into a dataframe and clean the data as necessary.
Separating the Data into Labels and Features- Create the labels set (y) from the “loan status” column, and create the features set (X) from the remaining columns.
Splitting Data- Split the dataset into training and testing sets.
Creating a Logistic Regression Model- Use a logistic regression algorithm to train models on the training data.
Evaluating Performance- Assess model performance using a confusion matrix, accuracy, precision, recall, and F1-score.

Method Used:  
A Logistic Regression Model was employed to predict loan status based on the provided financial features.

## Results

Machine Learning Model - Logistic Regression  

Accuracy: 0.99
Precision:
Class 0 (healthy loans) - 1.00
Class 1 (high-risk loans) - 0.87
Recall:
Class 0 (healthy loans) - 1.00
Class 1 (high-risk loans) - 0.89
F1-Score
Class 0 (healthy loans) - 1.00
Class 1 (high-risk loans) - 0.88

## Summary

The performance of Logistic Regression Model is excellent with the accuracy of 0.99, which means there is a high accuracy in prediction. The Precision and Recall scores are high, which represent 1.00 and 1.00 for healthy loans; 0.87 and 0.89 for high-risk loans respectively. Besides, the F1-score is high as well, with 1.00 for the healthy loans and 0.88 for high-risk loans. This model is particular well in identifying healthy loans, because it scores 1.00 in Precision, Recall and F1-Score. This model is recommended for predicting the loan status based on the overall high scores in every aspect. 

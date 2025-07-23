## Introduction 
Introduction: An anaylsis will be conducted for Beta Bank. Beta Bank is losing clientel and wants to determine which clientel they will be losing soon. Data is provided on clients' past behaviors and termination of contracts with the bank. The aim of the project will be to build a model with the maximum possible F1 score of at least 0.59. The following steps will be taken to achieve this aim: Once the data has been cleaned up, then dataframes will split both dataframe into training, validation and test sets. Then, a variety of machine learning classifier models including logistic reagression, decsion tree, and random forest will be used.In addition, I will examine the balance of classes in the target and develop models without balancing the classes. F1 scores and accuracy scores will be examined. The goal will be to achieve the highest possible F1 score with accuracy as a consideration. Next, downsampling and upsampling functions will be used to balance the numbers of postive and negative target classes, training and validation models will be used to preprocess data sets and choose the model with the highest F1 score. Once I have obtained the model's final F1 score using the testing set and I will find the AUC-ROC score. The AUC-ROC will need to be over 0.50. A sanity check will be conducted to ensure that the final model achieves this result not by random chance.

Purpose: The aim of this project is to answer the following questions: 
1.  Which model will most accurately predict customer churn rate?

## Data 
RowNumber — data string index 
CustomerId — unique customer identifier 
Surname — surname 
CreditScore — credit score 
Geography — country of residence 
Gender — gender 
Age — age 
Tenure — period of maturation for a customer’s fixed deposit (years) 
Balance — account balance 
NumOfProducts — number of banking products used by the customer 
HasCrCard — customer has a credit card 
IsActiveMember — customer’s activeness 
EstimatedSalary — estimated salary
Exited — сustomer has left

## Libraries Used 
Pandas, Numpy, Matplotlib, Scikit-Learn 

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Development and preparation of various models without balancing 
6.  Development and preparation of various models with balancing
7.  Selecting and evaluating the best performing model
8.  Conclusion 

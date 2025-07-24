## Introduction 
The purpose of this project is to identify customers at risk for churning for the company Interconnect. If a customer is at risk of leaving the company plans to offer promotional codes and special plan options. Interconnect provides two main services landline communication and internet. In addition the company provides device protection, online security, technical support, online backup, TV streaming and movie streaming services. The data provided by Interconnect was obtained from a variety of different sources and the information is valid as of February 1, 2020.

The project will aim to solve the following concerns:

What are some patterns shared by those who have churned?
What is the best machine learning model to accurately predict customer churn?
The objectives of the project will be to:

Identify patterns in behavior and demographics that seperate active customers from churned customers.
Design a machine learning model capable of accurately predicting customer churn with an accuracy score of at least .80 and AUC-ROC score of at least .85.

## Data 
Description for df_internet: 
customerID-Customer id.
InternetService- Type of internet service subscribed to by the customer.
OnlineSecurity- Indicates if customer has online security denoted by binary value of yes/no.
OnlineBackup- Indicates if customer has online backup service for data denoted by binary value of yes/no.
DeviceProtection-Indicates if customer has device protection service denoted by binary value of yes/no.
TechSupport- Indicates if customer has technical support service by binary value of yes/no.
StreamingTV- Indicates if customer has TV streaming service denoted by binary value of yes/no.
StreamingMovies-Indicates if customer has movie streaming service denoted by binary value of yes/no.

Description of data found in df_contract: 
customerID- Customer id
BeginDate- Start date of service
EndDate- Termination date of service. No indicates still using service.
Type-Contract type as indicated by month to month, one year, two year.
PaperlessBilling- Indicates if customer has paperless billing (yes/no)
PaymentMethod- Method in which payments are made (electronic check, etc).
MonthlyCharges-Amount that each customer pays on a monthly basis.
TotalCharges- Total amount charged to each customer during the duration of their contract.

Description for df_personal: 
customerID-Customer id
gender- Gender if the customer (Female or Male)
SeniorCitizen- Indiacates using 1/0 (aka binary) if a customer is classified as a senior citizen.
Partner- Indiacates using Yes/No (aka binary) if a customer has a partner. Dependents-Indiacates using Yes/No (aka binary) if a customer has a dependent.

Description for df_phone: 
customerID-Customer id. 
MultipleLines- Indicates if a customer has multiple lines indicated by a binary value of Yes or no.

## Libraries Used 
Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn, RE, Time, TQDM, Catboost,XGBoost, LightGBM,  

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing
4. EDA
5. Training Models
6. Model Evaluation
7. Testing Final Model Performance
8. Conclusion 

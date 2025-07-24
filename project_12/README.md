## Introduction 
Rusty Bargain, a used car sales service, requires an app to attract new customers. The app will enable users to quickly examine the market value of their cars. Users will have access to historical data, including technical specifications, and pricing. 

Purpose: The aim of this project is to do the following: 
1. Design a regression model to predict the car price. The model's effectiveness will be evaluated based on the following:
   a. Quality of the prediction
   b. Speed of the prediction
   c. Time required for training
   
## Data 
Features

DateCrawled — date profile was downloaded from the database

VehicleType — vehicle body type

RegistrationYear — vehicle registration year

Gearbox — gearbox type

Power — power (hp)

Model — vehicle model

Mileage — mileage (measured in km due to dataset's regional specifics)

RegistrationMonth — vehicle registration month

FuelType — fuel type

Brand — vehicle brand

NotRepaired — vehicle repaired or not

DateCreated — date of profile creation

NumberOfPictures — number of vehicle pictures

PostalCode — postal code of profile owner (user)

LastSeen — date of the last activity of the user

Target

Price — price (Euro)

## Libraries Used 
Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn, Time, Scipy, XGBoost, CatBoost, LightGBM

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing
4. EDA
5. Model Training
6. Model Evaluation
7. Model Testing
8. COnclusion

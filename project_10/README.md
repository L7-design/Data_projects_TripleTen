## Introduction 

Introduction: The aim of this analysis is to devise a machine learning model that can predict the amount of gold recovered from gold ore for the company Zyfra. The model will be designed to enhance the production process and remove unprofitable parameters for Zyfra. Zyfra is a company that is focused on crafting solutions to improve the process of mining gold. The dataset examined is from their warehouse. The following steps will be taken:

Data will be preprocessed including a verification that the recovery calculation is correct and comparison of the training set and the test set. Any missing values will be examined and targets choosen.
The concentrations for each metal at various stages will be compared and anything that needs to be removed. The feed size distributions between the training and test sets will be examined.
Models will be trained using various models.
The sMAPE scores will be calcualted and the superior scoring model will be choosen as the final mode. a. The model will be trained on the full training set and final sMAPE will be determined based on the test set. b. It will be compared to a dummy model.

Purpose: The project seeks to answer the following questions: 
1. Which parameters are unprofitable?
2. Which mode will best predict the amount of gold recovered? 

## Data 

## Libraries Used 
Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn, Tqdm 

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing
4. EDA
5. Training Models
6. Evaluating final model 
7. Conclusion 

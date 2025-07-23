## Introduction 

Mobile carrier Megaline has become aware that many subscribers remain on a legacy plan. Therefore, Megaline wants to develop a model that analyzes subscriber's behaviors to encourage subscribers to upgrade to a newer plan: Smart or Ultra. The data examined in this project will be based on data from subscribers who have already switched to one of the new plans offered by Megaline. The aim of this classification task will be to develop a model that will choose the right plan for the subscriber.

The model will need to have an accuracy threshold of 0.75. The models that will be tested will be decision tree classifcation, randrom forest classification, and logistic regression models for this goal threshold of 0.75. In order to ensure that the appropriate model is choosen the data will be split into a training set, validation set and a test set to ensure the same sets are used throughout the project. Furthermore, the hyperparameters will be tweaked to ensure the most effective model is selected. Finally, a sanity check will be performed to ensure that the chosen model performs better than random chance.

Purpose: The aim of the project is to answer the following questions: 
1. What classification model will have the best accuracy?

## Data 
calls: number of calls minutes

total call duration in minutes 

messages: number of text messages 

mb_used:internet traffic used in mb 
 
is_ultra: plan for the current month (ultra-1, smart-0)

## Libraries Used 
Pandas, Scikit-Learn

## Table of Contents 
1. Introduction
2. Data Exploration
3. Development and training of various classification models
4. Evaluation of highest performing model 
5. Sanity check on highest performing model 
6. Conclusion 

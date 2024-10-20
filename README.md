# Titanic - Machine Learning from Disaster
 
This repository contains a machine learning project aimed at predicting the survival of passengers aboard the Titanic using data from the famous Kaggle competition, "Titanic: Machine Learning from Disaster." In this project, I explore various machine learning techniques to predict whether a given passenger survived or perished during the Titanic disaster. The goal is to get familiar with essential machine learning workflows, such as data exploration, feature engineering, model selection, and performance evaluation.

## Problem Statement

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This project aims to predict which passengers survived the disaster using the available dataset, which includes variables such as age, sex, ticket class, and fare.

### Data Overview

#### The dataset is split into two parts:

 - train.csv - The training set with passenger details, including whether they survived.
 - test.csv - The test set used to make predictions.


#### Key features in the dataset:

 - PassengerId: Unique ID for each passenger.
 - Pclass: Passenger's class (1 = 1st, 2 = 2nd, 3 = 3rd).
 - Name: Name of the passenger.
 - Sex: Gender of the passenger.
 - Age: Age of the passenger.
 - SibSp: Number of siblings/spouses aboard the Titanic.
 - Parch: Number of parents/children aboard the Titanic.
 - Ticket: Ticket number.
 - Fare: Amount paid for the ticket.
 - Cabin: Cabin number (if available).
 - Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
 - Survived: Target variable (0 = Did not survive, 1 = Survived).

#### Key Learning Outcomes
This project helped me understand:

 - The fundamentals of data preprocessing and feature engineering.
 - How to work with imbalanced datasets where the target variable distribution is skewed.
 - Various classification algorithms and how to evaluate their performance.
 - The importance of hyperparameter tuning to boost model accuracy.
 - End-to-end machine learning workflow from data collection to model deployment.

#### Technologies Used
 - Python: The primary language used.
 - Pandas: For data manipulation and analysis.
 - NumPy: For numerical computations.
 - Scikit-Learn: For implementing machine learning models.
 - Matplotlib & Seaborn: For data visualization.
 - XGBoost: For advanced gradient boosting.
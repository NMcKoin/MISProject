# Titanic Machine Learning Project
## Overview
This project analyzes passenger data from the Titanic to build machine learning models capable of predicting passenger survival.

The project includes data cleaning, exploratory data analysis (EDA), feature selection, classification modeling, model evaluation, and performance tuning.

## Objectives
Clean and prepare the Titanic dataset
Handle missing values
Encode categorical features
Perform exploratory data analysis
Visualize relationships between features and survival
Identify important predictive features
Train and evaluate classification models
Compare model performance
Document findings and conclusions
Dataset


## The dataset contains passenger information including:

PassengerId
Survived
Pclass
Name
Sex
Age
SibSp
Parch
Ticket
Fare
Cabin
Embarked
Target Feature
Survived
0 = Did Not Survive
1 = Survived

## Data Preparation
The following cleaning steps were performed:

Removed Cabin due to a high number of missing values
Removed Name and Ticket text features
Filled missing Age values using the median age
Filled missing Embarked values using the most common embarkation point
Encoded Sex as numeric values
Encoded Embarked as numeric values
Exploratory Data Analysis


## EDA included:

Survival count visualization
Survival by gender
Survival by passenger class
Age distribution
Correlation matrix
Feature selection using SelectKBest
Machine Learning Models

## Models evaluated include:

K-Nearest Neighbors (KNN)
Logistic Regression


## Models are evaluated using:

Accuracy
Confusion Matrix
Classification Report
Feature Importance


## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook


## Author
Logan McKoin
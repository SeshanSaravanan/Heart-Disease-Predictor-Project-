# Heart Disease Predictor Project

This project aims to build a machine learning model to predict whether or not a person has heart disease based on their medical attributes. The project uses various Python-based machine learning and data science libraries to analyze the data, create predictive models, and evaluate their performance.

## Table of Contents

- [Problem Definition](#problem-definition)
- [Data](#data)
- [Evaluation](#evaluation)
- [Features](#features)
- [Tools Used](#tools-used)
- [Data Exploration](#data-exploration)
- [Modeling](#modeling)
- [Model Comparison](#model-comparison)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Conclusion](#conclusion)

## Problem Definition

In a statement, the problem can be defined as follows:

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## Data

The original data for this project comes from the Cleveland dataset available on the UCI Machine Learning Repository. A version of the dataset is also available on Kaggle.

[Link to the Kaggle dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

## Evaluation

The project's goal is to achieve a model accuracy of at least 95% in predicting whether or not a patient has heart disease during the proof of concept phase.

## Features

The dataset contains the following features:

- age: age in years
- sex: sex (1 = male; 0 = female)
- cp: chest pain type
  - Value 0: typical angina
  - Value 1: atypical angina
  - Value 2: non-anginal pain
  - Value 3: asymptomatic
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholesterol in mg/dl
- fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- restecg: resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach: maximum heart rate achieved
- exang: exercise-induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
  - Value 0: upsloping
  - Value 1: flat
  - Value 2: downsloping
- ca: number of major vessels (0-3) colored by fluoroscopy
- thal: 0 = normal; 1 = fixed defect; 2 = reversible defect
- target: 0 = no disease, 1 = disease

## Tools Used

The following Python libraries were used for this project:

- Pandas: Data analysis and manipulation
- Matplotlib: Data visualization
- Seaborn: Data visualization
- Scikit-Learn: Machine learning models (Logistic Regression, K-Nearest Neighbors, Random Forest)
- Jupyter Notebook: Development environment for the project

## Data Exploration

Exploratory data analysis (EDA) was conducted to understand the dataset better. This included analyzing data statistics, visualizing features, and examining the distribution of variables.

## Modeling

Three different machine learning models were employed to predict heart disease:

1. Logistic Regression
2. K-Nearest Neighbors Classifier
3. Random Forest Classifier

These models were trained and evaluated on the dataset to assess their performance.

## Model Comparison

The accuracy of each model was compared to determine which one performed the best for the given problem.

## Hyperparameter Tuning

Hyperparameter tuning was performed to optimize the K-Nearest Neighbors model. Different values of the number of neighbors (k) were tested to find the best-performing configuration.

## Conclusion

The Heart Disease Predictor Project aimed to predict the presence of heart disease based on medical attributes. The project involved data exploration, model training, and evaluation. The best-performing model achieved an accuracy of [insert accuracy]%. Further improvements and fine-tuning of models can be explored to enhance the predictive accuracy.

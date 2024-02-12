# Credit Card Approval Prediction

## Overview

This project focuses on predicting credit card approval decisions using machine learning models. The goal is to develop models that can efficiently assess the likelihood of approval for credit card applications based on various features.

## Dataset

The dataset used in this project contains information about applicants, including gender, car ownership, property ownership, income, employment details, education level, marital status, and more.

## Data Preprocessing

The data preprocessing steps include handling missing values, encoding categorical features, scaling numerical features, and splitting the dataset into training and testing sets.

## Models Explored

The project explores various machine learning classifiers for credit card approval prediction. These include:

- Stochastic Gradient Descent (SGD)
- Logistic Regression
- Decision Tree
- Random Forest
- Gaussian Naive Bayes
- K-Nearest Neighbors
- Gradient Boosting
- Linear Discriminant Analysis
- Bagging
- Neural Network
- AdaBoost
- Extra Trees

## Model Evaluation Metrics

Given the nature of the credit card approval prediction problem, the evaluation metric chosen is recall. The decision is based on the current economic situation, where the emphasis is on minimizing the risk of approving applications from potentially high-risk applicants.

## Top Model

After evaluating models using ROC curves and recall, the top-performing model is identified as the Gradient Boosting Classifier.

## Testing the Final Model

The final model, Gradient Boosting Classifier, is tested on a separate test dataset to assess its performance on unseen data.




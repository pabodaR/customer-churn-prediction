# Customer Churn Prediction Model

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [Results](#results)

## Introduction
Customer churn refers to the loss of clients or customers. This project aims to predict which customers are likely to churn using machine learning techniques.

## Project Overview
- **Objective:** Predict customer churn
- **Features:** Data exploration, preprocessing, model selection, evaluation, visualization

## Dataset
- **Source:** [https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset]
- **Description:** [
- his dataset is for ABC Multistate bank with columns, customer_id, credit_score, country, gender, age, tenure, balance, products_number, has_credit_card, is_active_member, estimated_salary, and exited, which is the churn variable used as the target. 1 if the client has left the bank during some period or 0 if he/she has not.]

## Data Preprocessing
- Handling missing values
- Handling duplicate values
- Encoding categorical variables
- Normalization/Standardization
- Feature scaling
- Feature engineering

## Modeling
- Models used: Logistic Regression, Decision Trees, Random Forest, SVM
- The performance of models against train and test sets were compared to select the most suitable model.

## Evaluation
- Metrics: Accuracy
-                         Train Accuracy  Test Accuracy
Logistic Regression           0.811375         0.8110
Decision Tree                 1.000000         0.7765
Random Forest                 1.000000         0.8675
Support Vector Machine        0.864750         0.8560

## Results
-   The Logistics regression model performs well in both train and test sets showing good generalization with no overfitting.

-   Decision tree model achieves perfect accuracy on the training set but shows poor performance on test data indicating lack of generalization on new data and overfitting of the model.

-   Random forest model also shows perfect accuracy on training set indicating overfitting, it shows lower performance on test data, however it is greater than that in Decision tree model.

-   SVM model performs well on both the training and testing sets. Its slightly higher training and testing accuracy compared to logistic regression.
  
-   Support Vector Machine (SVM) is recommended for this churn prediction task. It provides a good mix of training and testing accuracy without significant overfitting, making it a robust and reliable model for predicting churn



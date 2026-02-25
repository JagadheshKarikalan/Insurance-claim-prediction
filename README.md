# Insurance-claim-prediction

-- Insurance Claim Prediction & Risk Segmentation
- Project Overview

This project focuses on predicting whether a customer will file an insurance claim using machine learning techniques.

The objective is to:

Build a baseline classification model

Improve performance using XGBoost

Identify key risk drivers

Create interpretable risk segmentation

- Problem Statement

Insurance companies need to:

Identify high-risk policyholders

Reduce claim losses

Improve underwriting decisions

Price premiums based on risk

This project builds a predictive model to estimate claim probability and segment customers into risk categories.

- Project Workflow

Handled missing values

Performed exploratory data analysis (EDA)

Feature engineering

Encoding categorical variables

Train-test split

Baseline Model

Logistic Regression

Evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

- Advanced Model — XGBoost

Implemented XGBoost classifier

Tuned key hyperparameters

Achieved:

Accuracy: 83%

ROC-AUC: 0.90

XGBoost improved recall and overall model discrimination.

- Feature Importance Analysis

Top Risk Drivers Identified:

Driving Experience

Vehicle Year

Vehicle Ownership

Age

Driving experience was the strongest predictor of claim probability.

- Risk Segmentation

Two segmentation approaches were implemented:

- ML-Based Segmentation

Used predicted probability

Categorized into:

Low Risk

Medium Risk

High Risk

- Rule-Based Segmentation

Created an interpretable scoring system based on:

Low driving experience

Younger age

Older vehicle

Non-ownership

Each risk condition adds 1 point → final score determines risk level.

This provides business-friendly explainability.

- Model Evaluation

Confusion Matrix Analysis showed:

Good balance between recall and precision

Strong ROC-AUC indicating good class separation

The model effectively distinguishes between claim and non-claim customers.

- Business Impact

This model can help insurance companies:

Identify high-risk drivers early

Optimize premium pricing

Improve underwriting decisions

Reduce claim losses

Build data-driven risk scoring systems

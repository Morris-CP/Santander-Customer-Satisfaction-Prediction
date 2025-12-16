# Santander Customer Satisfaction Prediction
Machine Learning Project for Customer Dissatisfaction Risk Modeling

Binary Classification ｜ Feature Engineering ｜ Imbalanced Data ｜ SHAP Interpretability ｜ Tabular ML

## Project Overview
This project is based on the classic Kaggle competition  
**Santander Customer Satisfaction**.

The objective is to predict whether a customer is likely to be **dissatisfied** with their banking experience, using a high-dimensional dataset composed of anonymized features.

The model outputs a probability score that can be interpreted as a customer dissatisfaction risk indicator, enabling proactive monitoring and intervention.

## Technical Workflow
- Data preprocessing: missing value handling, sparse feature filtering  
- Feature engineering: statistical features and interaction-based transformations  
- Model training: XGBoost with cross-validation on imbalanced data  
- Model evaluation: ROC-AUC and comparative model analysis  
- Model interpretability: SHAP-based global and behavioral feature analysis  

## Key Results
- Final model (XGBoost) achieved an AUC of approximately **0.84** on the validation set  
- SHAP analysis reveals that customer dissatisfaction follows stable behavioral patterns related to account activity and product usage breadth  
- The model demonstrates strong interpretability and practical deployment potential as an early-warning system

## Dataset
Kaggle Competition:  
https://www.kaggle.com/competitions/santander-customer-satisfaction/overview

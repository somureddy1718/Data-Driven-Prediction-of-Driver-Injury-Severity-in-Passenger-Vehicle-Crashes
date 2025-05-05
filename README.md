# Data-Driven-Prediction-of-Driver-Injury-Severity-in-Passenger-Vehicle-Crashes
Data-Driven Prediction of Driver Injury Severity in Passenger Vehicle Crashes

Introduction

This project, conducted as part of the MSIS 5633 - Predictive Analytics Technologies course, focuses on predicting driver injury severity in passenger vehicle crashes using advanced machine learning techniques. By leveraging the Crash Report Sampling System (CRSS) dataset from the National Highway Traffic Safety Administration (NHTSA), the project aims to identify key factors influencing injury outcomes and develop predictive models to support proactive traffic safety measures. Following the CRISP-DM framework, the study encompasses data preparation, modeling, evaluation, and deployment planning, offering actionable insights for policymakers, safety agencies, and insurers.

Summary

The project systematically analyzes CRSS data to predict whether a crash results in minor or major driver injuries. Key steps include:

Data Preparation: Merged and cleaned relational datasets (accident, vehicle, person, distraction) using hierarchical keys (CASENUM, VEH_NO, PER_NO). Applied filtering to focus on passenger vehicle crashes with valid injury severity, handled missing values, and engineered features like vehicle age and overspeed indicators.


Modeling: Trained multiple machine learning models, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosted Trees, K-Nearest Neighbors, and Multilayer Perceptron. Gradient Boosted Trees achieved the highest performance with an AUC of 0.801, followed closely by Random Forest (AUC 0.789) and Logistic Regression (AUC 0.797).


Evaluation: Models were assessed using sensitivity, specificity, precision, accuracy, and AUC. Crash-specific factors like ejection status, restraint use, fire occurrence, and vehicle damage were identified as top predictors, emphasizing crash dynamics over demographic factors.


Deployment: Proposed integrating models into crash reporting systems, emergency response tools, and insurance platforms via KNIME WebPortal, with recommendations for threshold tuning, periodic retraining, and ethical considerations.

This repository provides a comprehensive framework for predicting injury severity, highlighting the potential of data-driven analytics to enhance road safety and inform policy interventions.

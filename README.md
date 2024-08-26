# CO2-emission-of-cars-L1-L2-Regularization

CO2 Emission of Cars Dataset

This repository contains an analysis of the CO2 Emission of Cars dataset, focusing on understanding and predicting vehicle emissions using regression techniques. The dataset includes various features related to car specifications and their CO2 emissions.

Dataset Overview

Columns:
* Car: Car make and model.
* Model: Specific model of the car.
* Volume: Engine volume in cubic centimeters.
* Weight: Car weight in kilograms.
* CO2: CO2 emissions in grams per kilometer.
* Unnamed: 5: (Contains NaN values; likely removed in preprocessing).

 Objectives
* Preprocessing: Clean and prepare data for modeling.
* Exploratory Data Analysis (EDA): Analyze relationships and distributions.
* Modeling: Apply Ridge and Lasso regression to predict CO2 emissions.
* Hyperparameter Tuning: Use GridSearchCV to find the best regularization parameters.
* Evaluation: Assess model performance using metrics such as Mean Squared Error (MSE).

Key Findings
* Comparison of Ridge and Lasso regression models.
* Impact of feature scaling on model performance.
* Optimal regularization parameters for each model.

# Summer-Heat-Waves-Mobile-Alert-System
This project aims to predict heat waves using historical weather data. By leveraging machine learning algorithms, we identify potential areas that might experience heat waves, helping authorities issue timely warnings and take necessary precautions.
* Project Overview
This repository contains the code and datasets used to develop and evaluate various machine learning models for predicting the next day's maximum temperature (Next_Tmax). The primary focus is on identifying areas where the temperature might exceed 40°C, thus indicating a heat wave.

* Key Features
Data Cleaning and Preprocessing: Handling missing values and scaling features.
Exploratory Data Analysis (EDA): Visualizing relationships between features and understanding data distributions.
Model Comparison: Evaluating different regression models to identify the best performer based on RMSE (Root Mean Squared Error).
Prediction and Warning System: Predicting temperatures for test data and issuing heat wave warnings for areas with predicted temperatures above 40°C.
* Datasets
Train Dataset: Historical weather data used for training the models.
Test Dataset: Data used for testing the model predictions and issuing heat wave warnings.
* Models Evaluated
Random Forest Regressor
Gradient Boosting Regressor
Linear Regression
Decision Tree Regressor
Support Vector Regressor (SVR)
XGBoost Regressor
CatBoost Regressor (Selected as the best model)
LightGBM Regressor
* Installation
To get started with this project, clone the repository and install the required dependencies:

bash
Copy code
git clone https://github.com/yourusername/heat-wave-prediction.git
cd heat-wave-prediction
pip install -r requirements.txt
Usage
Train the Model: The code provided reads the training data, preprocesses it, compares multiple models, and selects the best one for final predictions.
Predict and Warn: Using the test data, the model predicts the maximum temperature for each area and issues a heat wave warning if the temperature exceeds 40°C.

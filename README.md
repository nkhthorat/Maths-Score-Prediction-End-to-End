

# Title: Mathematics Score Prediction Software

## Description:
Our Mathematics Score Prediction Software is a comprehensive project developed using proper software development practices within Visual Studio Code. This project aims to predict math scores based on various input parameters. We have structured the project into multiple files and pipelines to ensure modularity and scalability.

## Key Components:

## Ingestion Pipeline: 
Responsible for fetching and preprocessing raw data. This pipeline ensures that data is properly formatted and cleaned before further processing.
## Transformation Pipeline: 
This pipeline handles feature engineering and data transformation tasks. It converts raw data into a format suitable for model training.
## Model Trainer: 
The heart of our project, this module trains predictive models on the transformed data. We have incorporated eight different algorithms for regression:
Linear Regression
K-Neighbors Regressor
Decision Tree Regressor
Random Forest Regressor
XGBRegressor
CatBoost Regressor
AdaBoost Regressor
Gradient Boosting Regressor
## Hyperparameter Tuning: 
Utilizing Grid Search CV, we optimize each algorithm's hyperparameters to enhance model performance. This step ensures that our models are fine-tuned and optimized for accurate predictions.
## Model Selection: 
We compare the performance of each algorithm using the R2 score and select the best-performing algorithm for our specific problem. In this case, Linear Regression emerged as the best algorithm based on our evaluation metrics.
## Model Persistence: 
After selecting the best algorithm, we train the final model using Linear Regression and save it for future use. This ensures that the trained model can be deployed and utilized efficiently.
## User Interface: 
To make our software accessible to users, we have developed a simple HTML page. This page allows users to input parameters and receive predictions for mathematics scores based on the trained model.

<img width="1118" alt="image" src="https://github.com/nkhthorat/mlproject/assets/50617471/416cb2d9-4b67-4079-8de0-848001acfa48">


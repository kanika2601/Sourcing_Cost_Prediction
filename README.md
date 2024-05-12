# Sourcing Cost Prediction Project

This project focuses on predicting the sourcing cost for a particular month using provided data. The goal is to develop machine learning models that accurately forecast the sourcing cost based on various features such as product type, manufacturer, area code, and sourcing channel.

## Overview

The project utilizes machine learning techniques, including linear regression, random forest, gradient boosting, and XGBoost regression, to predict the sourcing cost. It involves data preprocessing, feature engineering, model training, evaluation, and visualization of results.

## Models Used

- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression

## Graphs and Visualizations

The project includes various graphs and visualizations to analyze the data and model performance:
- Distribution of Sourcing Channels
- Histogram of Sourcing Channel
- Average Sourcing Cost by Manufacturer and Product Type
- Average Sourcing Cost by Product Size
- 'Average Sourcing Cost by Product Type
- Sunburst Graph of Area Code and Sourcing Channel

<p align='center'><a href="Screenshot 2024-05-12 at 10.39.34 PM.png" target="blank"><img align="center" src="https://github.com/Harsh-Ratna/Text-to-2d-Floorplan-Generation-using-GANs/blob/main/output%20images/real_vs_generated.jpg?raw=true" height="300" /></a></p>

## Requirements 
JupyterNotebook and anaconda enviroment
Python libraries : numpy , pandas , seaborn ,matplotlib , xgboost


## Conclusion On the Results

Based on the evaluation metrics obtained, the Random Forest Regression model outperforms the other models used in this project, including Linear Regression, Gradient Boosting Regression, and XGBoost Regression. With an R-squared (R^2) score of 0.938, the Random Forest model demonstrates the highest level of explained variance in predicting the sourcing cost for the given month. Additionally, it exhibits lower Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE) compared to the other models, indicating better overall performance in terms of accuracy and precision. Therefore, for this particular dataset and task of sourcing cost prediction, the Random Forest Regression model is recommended as the most suitable choice.


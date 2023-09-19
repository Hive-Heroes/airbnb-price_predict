# Airbnb Data Analysis and Price Prediction
This repository contains the code and materials for the Airbnb Data Analysis and Price Prediction project, completed as part of the MAT 388E course at @ITU. The goal of this project was to analyze Airbnb data from 2019 New York listings and develop models to predict prices.
## Contributors
- Berfin Duman
- Bike Sönmez
## Table of Contents
- Introduction
- Data Analysis and Visualization
- Preprocessing
- Price Prediction
- Regression
- Classification
- Conclusion
## Introduction
The Airbnb Open Data is an open-source platform that provides an overview of lodging options available at Airbnb locations. In this project, we focused on analyzing and predicting data from various Airbnb sites using the 2019 New York Airbnb listings dataset. The dataset includes information about the listings and their corresponding prices.

## Data Analysis and Visualization
In the data analysis phase, we imported the necessary libraries and performed exploratory data analysis (EDA) operations to gain insights into the dataset. We visualized features and examined their relationships. We also explored data distributions and identified common words in Airbnb apartment descriptions. These analyses helped us understand the dataset better.

## Preprocessing
Before including the dataset in the price prediction model, we conducted preprocessing operations. We dropped features that were not informative for price predictions, such as ID, last_review, host_id, name, and host_name. The dataset was divided into input features (X) and the target variable (y). We split the data into training and testing sets. Numeric values were filled with appropriate values and scaled, while categorical values were encoded using one-hot encoding. These preprocessing steps were performed using a pipeline and the ColumnTransform function.

## Price Prediction
## Regression
For price prediction, we created regression models using the training dataset. The following regression models were implemented:

- Linear Regression
- Lasso Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
We also performed hyperparameter tuning using GridSearchCV and RandomizedSearchCV to find the optimal parameters for all models except Linear Regression. The performance of each model was evaluated using train and test scores.

## Classification
In addition to regression, we experimented with classification models. Since the target variable was originally continuous, we transformed it into four categories to create a classification dataset. We ensured an equal distribution of classes by dividing the percentiles of the target variable into four intervals. The following classification models were implemented:

- Logistic Regression
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors Classifier
- Decision Tree Classifier
- Random Forest Classifier
Hyperparameter tuning was performed to optimize the performance of these models, except for Logistic Regression. The train and test scores were calculated to evaluate the classification models.

## Conclusion
Although the dataset did not yield the expected accuracy values, we explored various models and performed hyperparameter tunings to improve the prediction performance. The Gradient Boosting Regressor showed promising results in the regression task, while SVM performed better among the classification models. The repository contains notebooks and saved models for reference.

Thank you for your interest in our project! If you have any questions or feedback, please feel free to reach out.
- berfiinduman@gmail.com
- bikesnmz@outlook.com

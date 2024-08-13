# Bike Rental Prediction Project

## Overview
This project is part of the Introduction to Machine Learning course at the Leiden Institute of Advanced Computer Science. It involves analyzing and predicting bike rental volumes in a large European city using various machine learning techniques.

## Dataset
The dataset includes data about bike rentals along with various features like weather conditions, the day of the week, etc. The primary task is to predict the number of bikes rented by subscribers and non-subscribers.

## Problem Statement
The main learning objective is to predict the number of bikes rented using features provided in the dataset. This involves both regression to predict the total number of bikes and classification to categorize rental volumes into classes.

## Methods Used
- **Linear Regression**: To predict total bike rentals based on features.
- **Decision Tree Regressor**: Separate models for subscribers and non-subscribers.
- **SVM Regressor**: Examining different kernels and their impact on performance.
- **Random Forest**: Using various parameter tuning methods.
- **PCA**: Dimensionality reduction for feature analysis.
- **Clustering**: Hierarchical clustering to find intuitive groupings of data.

## Experiments
### Regression Analysis
Linear regression models were used initially, followed by decision tree and SVM regressors. The models' performances were evaluated using the R-squared metric, and parameter tuning was conducted to optimize results.

### Classification
The problem was transformed into a classification task by creating multiple binary classifications using logistic regression. Methods like one-vs-all and one-vs-one were compared.

### Feature Selection and Engineering
Feature selection was critical for the perceptron and SVM models. PCA was used to reduce dimensionality and to understand the importance of different features.

### Clustering
Hierarchical clustering was applied to explore natural groupings within the data. The results were visualized in 2D space using PCA.

## Results
- **Regression**: Best performing models and parameter configurations.
- **Classification**: Insights from logistic regression comparisons.
- **Feature Importance**: Key features influencing bike rental predictions.
- **Clustering**: Cluster characteristics and their relevance to the bike rentals.

## Conclusion and Future Work
Key findings include the effectiveness of various models and techniques in predicting bike rentals. Future work could explore more complex models or feature engineering techniques to improve prediction accuracy.

## Installation
To run this project, you will need Python and the following libraries:
- numpy
- pandas
- scikit-learn
- matplotlib


# Assignment_5_AIML3104

# Model Comparison Report

## Introduction

This report provides a comprehensive overview of the process and results of comparing Linear Regression and Artificial Neural Network (ANN) models using the California housing dataset. The goal is to analyze the performance of these models in predicting housing prices based on various features.

## Data Overview

The dataset used for this comparison is the California housing dataset. It includes various features such as median housing price, average rooms, bedrooms, population, and others. The dataset was split into training and testing sets, with 80% used for training and 20% for testing.

## Data Preprocessing

Before training the models, the features were standardized using `StandardScaler` to ensure that each feature had a mean of 0 and a standard deviation of 1. This step is crucial for models like Linear Regression and Artificial Neural Networks, which are sensitive to the scale of input features.

## Model Training

### Linear Regression

A Linear Regression model was trained on the standardized training data. Linear Regression is a simple and interpretable model that assumes a linear relationship between the features and the target variable.

### Artificial Neural Network (ANN)

An ANN model with two hidden layers (100 neurons in the first layer and 50 neurons in the second layer) was trained on the same standardized training data. ANN is capable of capturing complex, non-linear relationships in the data.

## Model Evaluation

Both models were evaluated on the testing set using two metrics: Mean Squared Error (MSE) and R-squared (R2) score.

### Linear Regression Results

- Mean Squared Error: *<insert 0.55 value>*
- R-squared (R2) Score: *<insert 0.57 value>*

### ANN Results

- Mean Squared Error: *<insert 0.27 value>*
- R-squared (R2) Score: *<insert 0.78 value>*

## Model Comparison

Linear Regression is a simpler model and performed well if the relationship between features and the target variable is approximately linear. However, ANN demonstrated its strength in capturing complex, non-linear relationships, achieving a lower Mean Squared Error and a higher R-squared score.

## Visualizations

Scatter plots were created to visualize the actual vs. predicted values for both Linear Regression and ANN models on the testing set. These plots help in understanding how well the models are capturing the underlying patterns in the data.

## Conclusion

In conclusion, the choice between Linear Regression and ANN depends on the complexity of the data. Linear Regression is suitable for simpler, linear relationships, while ANN excels in capturing intricate, non-linear patterns. Careful consideration of model complexity, interpretability, and dataset characteristics is essential in selecting the appropriate model for a given task. Additionally, tuning hyperparameters can further improve the performance of the models.

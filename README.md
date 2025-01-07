# Housing Price Prediction using Machine Learning & Deep Learning

This repository contains a project focused on predicting housing prices based on various factors such as location, number of rooms, median income, and other features related to housing in California. The project leverages both **Machine Learning** (KNN) and **Deep Learning** (Neural Networks) models for predicting the target variable: `median_house_value`.

## Overview

### Objective
The goal of this project is to predict the **median housing value** for regions based on several features. The dataset contains various aspects like the number of rooms, the population in an area, and its proximity to the ocean, among other things.

### Dataset
The dataset used is a comprehensive collection of data from California housing. Each data point represents a geographical area with features related to demographics and housing, and the target variable is the `median_house_value`.

The dataset includes the following columns:
- `longitude`: Longitude of the location
- `latitude`: Latitude of the location
- `housing_median_age`: The median age of the houses in the area
- `total_rooms`: Total number of rooms in the area
- `total_bedrooms`: Total number of bedrooms in the area
- `population`: The population of the area
- `households`: The number of households in the area
- `median_income`: The median income of the area
- `median_house_value`: The target variable (median house price)
- `ocean_proximity`: Whether the location is near the ocean or not (categorical feature)

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `Pandas`: Data manipulation and cleaning
  - `NumPy`: Numerical computations
  - `Scikit-learn`: For building Machine Learning models
  - `TensorFlow`/`Keras`: For building Deep Learning models
  - `Matplotlib`: Visualization of results
- **Development Environment:**
  - Jupyter Notebooks 

## Features of the Project

### Data Cleaning & Preprocessing
- Removed missing values.
- Encoded categorical variables (`ocean_proximity`) using one-hot encoding.

### Data Exploration & Visualization
- Analyzed the distribution of features and their relationships with the target variable (`median_house_value`).
- Visualized correlations between features.

### Models Built
#### 1. **K-Nearest Neighbors (KNN) Regressor**
- Implemented a KNN regression model using `Scikit-learn`.
- Evaluated the model using **Mean Squared Error (MSE)** and **R-squared** for accuracy.

#### 2. **Deep Learning Model (Neural Network)**
- Built a deep neural network using **Keras/TensorFlow**.
- Used **ReLU** activation functions in hidden layers and a linear output layer.
- Optimized with the **Adam optimizer** and used **Mean Squared Error (MSE)** as the loss function.

### Model Evaluation
- Predicted `median_house_value` using both KNN and the neural network.
- Visualized the performance of the models using **scatter plots** of actual vs. predicted values.
- Provided accuracy metrics: **MSE** and **R-squared** for both models.



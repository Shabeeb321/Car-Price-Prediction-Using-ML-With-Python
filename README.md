# Car Price Prediction Using Machine Learning With Python




https://github.com/user-attachments/assets/a5c3a7eb-9404-4e65-8d33-023ecbec832f








## Project Overview
This project implements a car price prediction model using two regression techniques: Linear Regression and Lasso Regression. The model predicts the selling price of cars based on various features such as fuel type, seller type, transmission, and other attributes. This project uses Python's pandas, matplotlib, seaborn, and scikit-learn libraries for data processing, visualization, and model training.

## Dataset
The dataset used in this project is a CSV file downloaded from Kaggle.com website containing car-related attributes such as:

1. Car_Name: Name of the car (dropped for modeling)
2. Year: Year of manufacture of the car
3. Selling_Price: Price at which the car is sold (target variable)
4. Present_Price: Current price of the car
5. Kms_Driven: Total kilometers driven by the car
6. Fuel_Type: Type of fuel used (Petrol, Diesel, CNG)
7. Seller_Type: Whether the seller is an individual or a dealer
8. Transmission: Transmission type (Manual or Automatic)
9. Owner: Number of previous owners of the car
  
The dataset is loaded from car_dataset.csv and is cleaned and preprocessed for modeling.

## Key Steps
1. Data Collection and Preprocessing:
Loaded the dataset from a CSV file.
Inspected the first few rows and checked the number of rows and columns.
Handled missing values and performed data encoding on categorical variables (Fuel_Type, Seller_Type, Transmission).
Split the dataset into features (X) and the target variable (Selling_Price).

3. Model Training:
Linear Regression Model: Trained a linear regression model to predict car prices using the features.
Lasso Regression Model: Applied Lasso regression for regularization and model training.

5. Model Evaluation:
Evaluated both models using R-squared as the evaluation metric to measure the accuracy of predictions.
Visualized the relationship between actual and predicted prices using scatter plots for both training and test data.

7. Results Visualization:
Visualized the performance of the models by plotting actual prices against predicted prices.
Plots show the accuracy and performance of each model.

## Project Links

Google Collab File: https://colab.research.google.com/drive/1NaWXHCffiZAdYa6Oz_DY2Ev2erdhhIvP#scrollTo=pdUrZlsrv39Z
Dataset: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

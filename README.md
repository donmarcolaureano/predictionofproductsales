# Project Overview
Author: Marco Laureano

**Business Problem**
- The purpose of this project is to project the product sales for food items sold at various stores.
- The goal is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales

## Data 
[Link to Raw Data](sales_predictions_2023.csv)

## Methods
With the data provided, we were able to process and create four different machine learning models that could explain for 59% of testing data.
  - Linear Regression (~57%)
  - Default Random Forest (56%)
  - Tuned Random Forest (59%)

In addition to the models, we were able to plot find out quite a lot of information about each store and the sales of each product.

## Results
Based off of the different models, I would recommend using the tuned Random Forest model as it outperformed both the Linear Regression and default Random Forest model on MAE, MSE, RMSE, and R^2 for the testing data
- The tuned Random Forest model is very comparable to the Default Random Forest model in many ways. The Default model actually outperformed the Tuned model in the training data but fell short on the data that mattered, the test data.
- Despite the Linear Regression model and Default Random Forest model having large differences in the training data, they both performed fairly similar on the test data
  - The R^2 metric is very important. It shows that the model can explain a specific % of the data.
  - The Linear Regression model can explain ~57% of the test data
  - The Default Random Forest model can explain 56% of the test data
  - The Tuned Random Forest model can explain for 59% of the test data



### Products sold by item type
![Prediction of products sold_sales by item Type](https://github.com/donmarcolaureano/predictionofproductsales/assets/140132043/d621f481-9983-4da1-9da6-4931aa194c73)
- Fruits and vegetables were the highest selling category
#
### Sales by outlet type
![Prediction of product sales_Sales By Outlet Type](https://github.com/donmarcolaureano/predictionofproductsales/assets/140132043/230562c9-4180-4d20-a578-5c2bfa6e7ca0)
- Supermarket Type 1 sold a significant more than the other outlet types
#
### Numeric Heatmap
![Sales Predicitons Heatmap](https://github.com/donmarcolaureano/predictionofproductsales/assets/140132043/650373a2-05a9-46f9-8df4-8d83da381f67)
- Item Weight & Item MRP had the highest correlation
#
### Boxplot
![Sales Predictions Box Plot](https://github.com/donmarcolaureano/predictionofproductsales/assets/140132043/9671b04f-34cc-421d-8eb2-6ed3a59c22c7)
- The oldest established outlet had the highest number of product sales

# Food_Demand_Forecasting

## Problem Statement:

The main aim of this project is to create an appropriate machine learning model to forecast then number of orders to gather raw materials for next ten weeks. we should know the information about of fulfilment center like area, city etc. and meal information like category of food sub category of food price of the food or discount in particular week. By using this data, we can use any classification algorithm to forecast the quantity for 10 weeks.

## Detailed-Steps: 

*STEP 1: Understanding data and Importing Libraries.

       * Libraries Imported: 
       
         import pandas as pd
         
         import numpy as np
         
         import matplotlib.pyplot as plt
         
         import seaborn as sns
         
         from sklearn.preprocessing import LabelEncoder
         
         from sklearn import metrics
         
         from sklearn.model_selection import train_test_split
         
         from sklearn.linear_model import LinearRegression
         
         from sklearn.neighbors import KNeighborsRegressor
         
         from sklearn.tree import DecisionTreeRegressor
         
         from sklearn.ensemble import GradientBoostingRegressor
         
         from xgboost import XGBRegressor
         
  
* STEP 2: Loading Dataset:

          Loading the dataset by using .csv file.
  
* STEP 3: Data Cleaning And Data pre-processing:

          * Checking null values.
          * Removing duplicates.
          * Statistical measures.
          * Merging the values.
  
* STEP 4: EDA And Lable Encoding.

   Explorating the 'orders Distribution' and categorical columns performed as label encoding.
  
![1693731589466](https://github.com/rakshithaelango/Food_Demand_Forecasting/assets/116090323/74eca4f5-3dfb-4a34-8494-d85eb95d2dc0)

* STEP 5: Correlation by using heatmap

 ![1693731589462](https://github.com/rakshithaelango/Food_Demand_Forecasting/assets/116090323/431d0359-d01d-450c-a62d-da8da01248bd)
 
* STEP 6: Splitting the dataset into train - test split and Model Building.

        * Splitting the dataset:

         X_train, X_val, y_train, y_val = train_test_split(X, y, test_size=0.25).

        * Model Building:
          
![1693731589472](https://github.com/rakshithaelango/Food_Demand_Forecasting/assets/116090323/270921f6-5c26-4423-985d-4db6b3d759f4)

## Dataset link:
https://www.kaggle.com/datasets/kannanaikkal/food-demand-forecasting




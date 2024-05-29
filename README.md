# POWER CONSUMPTION PREDICTION

## Introduction 
Power consumption prediction refers to the process of estimating future energy use by analyzing past power consumption patterns and other relevant factors, such as weather conditions, time of day, and industrial activity. Accurate predictions are essential for efficient energy management, grid stability, and cost reduction.

## Overview
The goal of this project is to create a machine learning model capable of accurately predicting power consumption in Zone 3. The dataset includes various features that influence power consumption, and these features are described below:

|Sr.no|Features name|Description |
 |-|-|-|
|1)|Datetime| The date and time of the recording|
|2)|Temperature|The Temperature in Celsius|
|3)|Humidity| The concentration of water vapor in the air|
|4)|WindSpeed|The speed of the wind in kilometers per hour|
|5)|GeneralDiffuseFlows| The measurement of how much emissions gases diffuse into the broader atmosphere|
|6)|DiffuseFlows| The measurement of how much emissions gases diffuse into the local |
|7)|PowerConsumption_Zone1|The power consumption in Kilowatt-Hours in Power Zone 1|
|8)|PowerConsumption_Zone2|The power consumption in Kilowatt-Hours in Power Zone 2|
|9)|PowerConsumption_Zone3|The power consumption in Kilowatt-Hours in Power Zone 3|

 ## Steps performed
 1. Import Libraries : 
    Load the necessary Python libraries for data analysis
 2. Import Data :
    Import the dataset containing the features and target variable   
 3. Data Clean :
    Check Null values, Duplicated values
 4. Data Understanding :
    Perform exploratory data analysis to understand the distributions
 5. Feature Engineering :
    Created new features from Datetime column:
    1. Year
    2. Month
    3. Day
    4. Hour
    5. Minute
    6. Date
    7. Time
    8. Week    
 6. Data Visualizations :
    Visualize the data to gain insights and detect trends    
 7. Feature Selection :
    See the most relevant features for the modeling process
 8. Deep Learning :
    Develop and evaluate deep learning models
    1) ANN Model
    2) LSTM Model
 9. Machine Learning :
    Develop and evaluate machine learning models
    1) Linear Regression
    2) Decision Tree
    3) Random Forest
    4) Support Vector Regression
    5) K-Nearest Neighbors
    6) XGBoost
10. Testing :
    Best model selected is Decision Tree Regressor (Reason - R2 score is good, as well as MSE is less) 




    



    








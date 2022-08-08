# Bike Sharing Assignemnt
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Provide general information about your project here.
A linear Regression Model has been build to analysis the impact of the driving features based on the vaialble data set, for predicting the demand of shared bikes with respect to the descriptions of the variables in the data dictionary available in the below link:
https://drive.google.com/file/d/1x4Vi_FF0DEmTN1Cf6BnPHUuQP9p0s0Pz/view

   Step 1: Data Understanding
   Step 2: Exploratory Data Analysis (EDA)
   Step 3: Creating Dummy Variables for the Categorical Data
   Step 4: Dividing the data into Train & Test Sets
   Step 5: Scaling the Train Data using MinMax Scaler
   Step 6: Using RFE to find out the top 15 features that influence the dependent variable i.e 'cnt'
   Step 7: Building a linear model using StatsModel
   Step 8: Checking the R-Squared, Adjusted R-squared, F-statistics and correlation coeff to uderstand the model's accuracy
   Step 8: Using Manual Feature Elimination process to eliminate features from the Model based on high p-Value & VIF 
   Step 9: Continue building Model to arrive a the best possible model with lowest p-Value and VIF for the variables and decent R-Squared, Adjusted R-squared, F-statistics and correlation coeff
   Step 10: perform Residual Analysis on the model to ensure stability and accuracy
   Step 11: Using the Model on the Test Set to make predictions (after scaling the test data set)
   Step 12: Compairing the R-Squared & Adjusted R-Squared of the Model on Train and Test data set to determine the efficiency of the model
   Step 13: Conclude on the top parameters and their coefficient influence on the predictor/dependent variable by arriving at the best model equation
 
- What is the background of your project?

Build a linear model for the demand for shared bikes with the available independent variables. Which will be used by the management to understand how exactly the demands vary with different features. So that they can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- What is the business probem that your project is trying to solve?

Building an ML Model for predicting the demand of shared bikes

- What is the dataset that is being used?
Complete shared bike data data for BoomBikes for the year 2018-2019


## Conclusions
As per the final model, the top predictor variables are:
1. yr : A coefficient value of 0.2308 indicates that a unit increase in yr increases the bike bookings by 0.2308 units
2. temp : Unit increase in temperature increases bike hiring by 0.5977 units
3. hum : increase in humidity by a unit decreases the bike hiring by 0.2192 units
4. windspeed : bike bookings decreases by 0.1654 units with unit increase in windspeed
5. season_4 : i.e 'Winter' season as per data dictionary indicates bike hiring increase by 0.1487 units
6. weathersit_3 : unit increase in weather situation3 i.e Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds decrease bike hiring by 0.1422 units
7. mnth_9 : September month sees an increase in bike hiring by 0.0990 units
8. season_2 : Summer season impacts the bike hiring with an increase by 0.0864 units


## Technologies Used
- Python Version: 3.9.7
- Pandas Version: 1.3.4
- Numpy Version: 1.20.3
- MatplotLib Version: 3.4.3
- Seaborn Version: 0.11.2
- Statsmodels Version: 0.12.2
- SkLearn Verdion: 0.24.2

  Jupyter Notebook with Python code detailing the approach used for analysis
  Python Numpy library for data evaluation
  Pandas library to get an insight into the data frame
  Matplotlib and Seaborn to create various visualization charts for beter represntation and interpretation of data
  StatsModels for model building and statistical analysis
  Scikilearn for scaling the data, slitting the data and automated model building using RFE 
  Scikilearn for checking the r2_score


## Acknowledgements
- This project was based on UpGrad AIML Course Assignment

## Contributors
   - Madhusmita Paul
  
## Contact
-Created by [@PaulMadhusmita]  - feel free to contact me!
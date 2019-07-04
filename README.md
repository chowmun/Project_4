# West Nile Virus Kaggle Competition

<https://www.kaggle.com/c/predict-west-nile-virus/>

![GA logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

## General Assembly - Data Science Immersive 8

### Project 4

#### Team members: Alfred Tang, Chow Mun Yang, Ferdi Garcia, Jay Lee, Michael Xiao

## Problem Statements

1. How can we correctly predict the presence of WNV-positive mosquitoes?

2. What features are most predictive of WNV-positive mosquito breeding behaviour?

3. What actions can be taken as a long-term solution to the spread of diseases by mosquitoes?

### Executive Summary

Logistic Regression, XGBoost and BernoulliNB were used to predict WnVPresent. Out of the three models, XXX model gives the best results with precision/recall scores of xx/xx.

Our findings: ![visualisation](https://github.com/chowmun/Project_4/tree/master/misc/proj4_vis.pdf)

#### Feature Engineering

Data dictionary:

Feature Name    | Description
--------------- | -------------------------------------------------------------------------------------------------------------------------
AddressAccuracy | Accuracy score of Address (out of 10)
WnvPresent      | Target; West Nile Virus Presence
dist_ohare      | Maximum Temperature
dist_mid        | Minimum Temperature
sprayed         | Area that had been sprayed in the last 3 days
temp_spread     | Temperature spread (Tmax - Tmin)
PrecipTotal     | Water equivalent (inches & hundredths(2400 LST) rainfall & melted snow
Tavg_1          | average temperature in °F
r_humidity      | Relative humidity in °C
len_day_1       | Length of the day in minutes (Sunset - Sunrise)
Species         | CULEX PIPIENS,CULEX PIPIENS/RESTUANS,CULEX RESTUANS, CULEX SALINARIUS, CULEX TARSALIS, CULEX TERRITANS, CULEX UNSPECIFIED
month           | Months of May, June, July, October

Legend | Description
------ | ------------
M      | Missing data
T      | Trace

Original data dictionary: [Click to Download](~/noaa_weather_qclcd_documentation.pdf)

#### Modelling Results

##### Logistic Regression

![logreg_classrep](https://github.com/chowmun/Project_4/tree/master/misc/logreg.jpg)

##### XGBoost

![xgboost_classrep](https://github.com/chowmun/Project_4/tree/master/misc/XGB.jpg)

##### BernoulliNB

![bnl_classrep](https://github.com/chowmun/Project_4/tree/master/misc/bnl.jpg)

#### Limitations

- absence of meaningful data to address mosquito breeding behaviour

#### TL;DR

- Model results

_Visualisation_ ![click here](https://github.com/chowmun/Project_4/tree/master/misc/proj4_vis.pdf)

- Sprays are only effective if done regularly
- Precipitation correlates with sum of numMosquitos (makes sense as water activates the eggs and is needed for procreation)
- Temperature has a positive correlation with mosquito activity

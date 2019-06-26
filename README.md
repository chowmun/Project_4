# West Nile Virus Kaggle Competition
https://www.kaggle.com/c/predict-west-nile-virus/

![GA logo] <img src='/general-assembly_logo.png' />

## General Assembly - Data Science Immersive 8
### Project 4 
#### Team members: Alfred Tang, Chow Mun Yang, Ferdi Garcia, Jay Lee, Michael Xiao

## Problem Statement
1. Given historical data, how can we access and locate West-Nile virus positive mosquitoes and significantly mitigate the outspread of its disease?

2. What can environmental trends tell us about mosquito breeding behaviour? 

3. What recommendations can we provide in order to decrease the spread of mosquito-related diseases in the long run?

### Executive Summary

The purpose of this challenge is to determine where and when have the highest west nile activity in our data and which species of mosquitoes are more proned to carry this disease.

#### Feature Engineering

Data dictionary (weather):

| Feature Name | Description   |
|--------------|---------------|
| Station      | Station         |
|  Date        | Date expressed in YYYY-MM-DD          |
| Tmax       | Maximum Temperature         |
| Tmin       | Minimum Temperature        |
| Tavg       | Average Temperature         |
| Depart       | temperature that departs from normal        |
| DewPoint       | average Dew Point temperature          |
| WetBulb       | average Wet Bulb temperature          |
| Heat       | Heating (Season begins with July) (Base = 65°F)         |
| Cool       | Cooling (Season begins with January) (Base = 65°F)          |
| Sunrise       | Sunrise  (Calculated, not observed)        |
| Sunset       | Sunset  (Calculated, not observed)         |
| Depth       | Snow/ice (on ground)(1200 UTC)|
| Water1       | Water equivalent (1800 UTC)|
| SnowFall       | Snowfall (inches and tenths)(2400 LST)   |
| PrecipTotal       | Water equivalent (inches & hundredths(2400 LST) rainfall & melted snow |
| StnPressure       | Average station pressure      |
| SeaLevel       | Average sea level pressure        |
| ResultSpeed       | Resultant wind speed        |
| ResultDir       | Resultant direction in whole degrees       |
| AvgSpeed       | Average speed   |
| weekday_name       | Day name in Date feature          |
| day       | Day in Date feature          |
| month       | Month name in Date feature          |
| year       | Year in Date feature          |
| temp_spread       | Temperature spread (Tmax - Tmin)          |
| Tavg2       | Tavg feature in °C         |
| r_humidity       | Relative humidity (Tavg2 and DewPoint in °C)        |
| len_day       | Length of the day in minutes (Sunset - Sunrise)      |

| Legend | Description   |
|--------|---------------|
| M | Missing data|
| T | Trace|


<a download="Data_dictionary.pdf" href="/Users/michaelxiao/Desktop/Data_dictionary.pdf" title="Data_dictionary_WnV">
</a>

#### Data Preprocessing 

#### Modelling 

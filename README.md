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

### [Key Findings](https://drive.google.com/open?id=1GgcDXulfHbrNPDNhaW0eWYGpN-6djV1x)

#### Feature Engineering

Data dictionary:

|Feature Name    | Description|
|--------------- | ------------------------------|
|AddressAccuracy | Accuracy score of Address (out of 10)|
|WnvPresent      | Target; West Nile Virus Presence|
|dist_ohare      | linear geographic distance between latlong of observation and latlong of Chicago O'Hare airport|
|dist_mid        | linear geographic distance between latlong of observation and latlong of Chicago Midway airport|
|sprayed         | Area that had been sprayed in the last 3 days|
|temp_spread     | Temperature spread (Tmax - Tmin)|
|PrecipTotal     | Water equivalent (inches & hundredths(2400 LST) rainfall & melted snow|
|Tavg_1          | average temperature in °F|
|r_humidity      | Relative humidity |
|len_day_1       | Length of the day in minutes (Sunset - Sunrise)|
|Species         | CULEX PIPIENS,CULEX PIPIENS/RESTUANS,CULEX RESTUANS, CULEX SALINARIUS, CULEX TARSALIS, CULEX TERRITANS, CULEX UNSPECIFIED|
|month           | Months of May, June, July, October|

Legend | Description
------ | ------------
M      | Missing data
T      | Trace

Original data dictionary: [Click to View](https://github.com/chowmun/Project_4/tree/master/assets/noaa_weather_qclcd_documentation.pdf)

#### Recommendations
1. Maintain healthy levels of natural predators to keep mosquito population at bay
    - Birds, spiders, dragonfly nymphs and diving beetles are natural predators of mosquito larvae, while dragonflies, birds and bats feed on adult mosquitoes.
    - Infected animals cannot transmit to humans unless via a mosquito bite
2. Good mosquito control practices can help reduce mosquito breeding at home
    - Keep your home mosquito free with this detailed [guide](https://www.researchgate.net/publication/315924484_Best_Practices_for_Integrated_Mosquito_Management_A_Focused_Update)
    - Trap mosquitos that are currently trespassing in your property. Set a [trap](hhttps://www.wikihow.com/Make-a-Plastic-Bottle-Mosquito-Trap) 
    - Practice the 3Rs' from the redlineproject [link](http://redlineproject.org/westnilevirus.php)
3. Read up on West Nile Virus and know what preventive measures to take
    - [Understand the problem](http://www.idph.state.il.us/public/hb/hbwestnile.htm)
    - [Preventing West Nile Virus](https://www.chicago.gov/city/en/depts/cdph/supp_info/infectious/preventing_west_nilevirus.html)

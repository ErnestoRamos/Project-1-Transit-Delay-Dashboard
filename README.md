# Transit Delay Dashboard and Predictor

- Aggregated publicly available bus and streetcar delay data between 2014 to 2019 (via open data Toronto) to discover trends in delay type, length of a delay, vehicle type, delay by year, delay by season and delay by hour.
- Used address provided from dataset to collect over 70k geolocations via open street maps and google maps api
- Used tableau to create an interactive dashboard which can be viewed in more detail here: https://public.tableau.com/profile/eramos4256#!/vizhome/TTCBusDelayEDA/Dashboard1  
- Created a to of delay type using ML and DL - attempted to build a model (using ML and DL) which predicts the type of delay that will occur given an hour, day, and geolocation of the vehicle

# Code and Resources Used
Python Version: 3.8
Packages: pandas, googlemaps, geopy, numpy, sklearn, xgboost, tensorflow


![Dashboard](https://user-images.githubusercontent.com/56518821/111860831-8f3c8900-8920-11eb-8521-83d2c0b7890c.png)






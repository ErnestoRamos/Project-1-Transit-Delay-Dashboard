# Transit Delay Dashboard 

- Aggregated publicly available bus and streetcar delay data between 2014 to 2019 (via open data Toronto) to discover trends in delay type, length of a delay, vehicle type, delay by year, delay by season and delay by hour.
- Used address provided from dataset to collect over 70k geolocations via open street maps and google maps api
- Used tableau to create an interactive dashboard which can be viewed in more detail here: https://public.tableau.com/profile/eramos4256#!/vizhome/TTCBusDelayEDA/Dashboard1  

# Code and Resources Used
- Python Version: 3.8
- Packages: pandas, googlemaps, geopy

# Date Cleaning 
- merged 2014 - 2019 files for bus and streetcar 
- parsed year, month, and day from report date and converted to datetime format
- cleaned provided location for address consistency to be used as input for geopy and google maps api

![Dashboard 1](https://user-images.githubusercontent.com/56518821/111861291-6b2e7700-8923-11eb-9729-2ab3fbdbac8d.png)







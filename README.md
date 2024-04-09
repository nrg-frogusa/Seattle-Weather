# Seattle vs. New York Weather
We will analyze and compare weather data from New York and Seattle. The purpose is to determine in which state it rains more, in both frequency and magnitude. 

# Data
We will use daily precipitation measured between January 1st, 2020 and January 1st, 2024, gather through the National Centers for Environmental Information. 

https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

# Data Preparation
First, we examined an overview of the shape of the data, learning some basic information about it. 
Then, we dropped unecessary variables that wouldn't help our exploration of Seattle vs. New York weather.
Also, we joined/merged both datasets together to create a consolodated dataframe that has all relevant data in one place. It uses a "city" variable to differentiate precipitation and date values.
Lastly, we removed duplicate and Null values from our dataset where we could. 

The file used to clean and prepare the data is called "Seattle_NYC_Weather.ipynb".

The clean dataset that's ready for analysis is called "clean_seattle_nyc_weather.csv".

# Seattle vs. New York Weather
We will analyze and compare weather data from New York and Seattle. The purpose is to determine in which state it rains more, in both frequency and magnitude. 

# Description
This repository contains all necessary documents, Colab notebooks, and analyses required to satisfy the purpose stated above. We utilized data visualization and analyses principles to accurately and responsibly conclude that it rains "more" in New York.

# Data
We will use daily precipitation measured between January 1st, 2020 and January 1st, 2024, gather through the National Centers for Environmental Information. The data was collected through a series of weather stations in Seattle and New York. 

https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

# Data Preparation
First, we examined an overview of the shape of the data, learning some basic information about it. 
Then, we dropped unecessary variables that wouldn't help our exploration of Seattle vs. New York weather.
Also, we joined/merged both datasets together to create a consolodated dataframe that has all relevant data in one place. It uses a "city" variable to differentiate precipitation and date values for Seattle and New York respectively.
Lastly, we removed duplicate and Null values from our dataset where we could. 

The file used to clean and prepare the data is called "Seattle_NYC_Weather.ipynb".

The clean dataset that's ready for analysis is called "clean_seattle_nyc_weather.csv".

Both can be found within this repository.

# Data Analysis
First, I posed some questions that I thought would be important to understanding in which city it rains "more". I thought of average rainfall in each city, the standard deviation of values for precipitation measures, the frequency of rainfall greater than 0.25 inches, and in which months the average rainfall is less than 0.1 inches.
Next, I utilized plots and visualizations to give context to the mean and standard deviation values I found. It became clear that both frequency and magnitude of rain were the most important aspects to consider when thinking about where it rains "most".

# Requirements
Programs and packages required to perform the analysis are as follows: Google Colab, pandas, matplotlib, numpy, and seaborn. All packages can be downloaded directly to Google Colab. 

# Author
Justin Ishida
LinkedIn: www.linkedin.com/in/justin-ishida

# License
All are allowed to download, repliate, improved upon, and manipulate the analyses done in this repository. Furthermore, all are allowed to use my findings and analysis for their own personal or professional projects should it add value to their own work. 

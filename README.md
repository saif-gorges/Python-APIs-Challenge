# Matplotlib Challenge - Pymaceuticals Inc.

## Table of Contents
  * [Introduction](#introduction)
  * [API Keys](#api)
  * [Observations](#observations)
  * [Data Visualization](#data-visualization)
    * [Temperature (F) vs. Latitude](#temp)
    * [Humidity (%) vs. Latitude](#hum)
    * [Cloudiness (%) vs. Latitude](#clo)
    * [Wind Speed (mph) vs. Latitude](#win)
    

# Introduction

The purpose of this project was to create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API to create a representative model of weather across world cities.
I have built a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

# API Keys

The script uses the OpenWeatherMap API; therefore, to run this jupyter notebook, the OpenWeatherMap API keys will be required.

The API key is available <a href="https://home.openweathermap.org/users/sign_in">here</a> after creating an account and signing in.

Before running the notebook, make sure to create 'api_keys.py' file with api_key = "Type your api key here" in the 'WeatherPy' folder.

# Observations

- From the latitude vs. longtitude plot, we can conclude that as we approach the equator the weather becomes warmer. It is also important to note that there is a wider range of temperature differences for cities that are in the lower hemisphere.
- From the latitude vs. humidity plot, we can conclude that there is no strong correlation.
- From the latitude vs. cloudiness plot, we can conclude that there is no strong correlation.
- IFrom the latitude vs. windiness plot, we can conclude that there is no strong correlation.



# Data Visualizations

## <a name="lat">Temperature (F) vs. Latitude</a>
Bar plot using both Pandas's and Matplotlib's that shows  the number of total mice for each treatment regimen throughout the course of the study.<br>
![image](https://github.com/saif-gorges/python-APIs-challenge/blob/main/latitude_vs_temp.png)


## <a name="lat">Humidity (%) vs. Latitude</a>
Pie plot using both Pandas's and Matplotlib's that shows the distribution of female or male mice in the study.<br>
![image](https://github.com/saif-gorges/python-APIs-challenge/blob/main/latitude_vs_humidity.png)


## <a name="clo">Cloudiness (%) vs. Latitude</a>
Box and whisker plot of the final tumor volume for all four treatment regimens.<br>
![image](https://github.com/saif-gorges/python-APIs-challenge/blob/main/latitude_vs_cloudiness.png)


## <a name="win">Wind Speed (mph) vs. Latitude</a>
Visualization of tumor volume vs. time point a mouse that was treated with Capomulin.<br>
![image](https://github.com/saif-gorges/python-APIs-challenge/blob/main/latitude_vs_wind_speed.png)

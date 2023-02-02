# python-api-challenge
Module 6 Challenge

This repository has two folders:
1) Output Data
 - Contains the output csv files and images (.png)
2) Starter Code
 - Contains the Jupyter notebook
 - WeatherPy.ipynb and VacationPy_ipnyb

Module 6 Assignment for Python APIs

Part 1: WeatherPy
In this deliverable, we will create a Python script to visualize the weather of over 500 cities of varying distances from the equator. 
We will use the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site.
For Part 1, we will use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, create a series of scatter plots to showcase the following relationships:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
Define a function in order to create the linear regression plots.
Create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.
  - Northern Hemisphere: Temperature vs. Latitude
  - Southern Hemisphere: Temperature vs. Latitude
  - Northern Hemisphere: Humidity vs. Latitude
  - Southern Hemisphere: Humidity vs. Latitude
  - Northern Hemisphere: Cloudiness vs. Latitude
  - Southern Hemisphere: Cloudiness vs. Latitude
  - Northern Hemisphere: Wind Speed vs. Latitude
  - Southern Hemisphere: Wind Speed vs. Latitude
After each pair of plots, explain what the linear regression is modeling. Describe any relationships and any other findings uncovered.


Part 2: VacationPy
Use the weather data to plan future vacations. In part 2, we will use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
The main tasks is to use the Geoapify API and the geoViews Python library to create map visualizations.

Using the VacationPy.ipynb starter code, we will complete the following steps:
1) Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
2) Narrow down the city_data_df DataFrame to find your ideal weather condition.
3) Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4) For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5) Add the hotel name and the country as additional information in the hover message for each city on the map.


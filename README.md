# python_api_challenge

Instructions

This activity is broken down into two deliverables, WeatherPy and VacationPy.

Part 1: WeatherPy

In this section, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library which links to an external site, the OpenWeatherMap API, and used problem-solving skills to create a representative model of weather across cities.

I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I created a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Next, I computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude), and created a series of scatter plots.

Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, I explained what the linear regression is modeling. 

Part 2: VacationPy

In this section, I used use my weather data skills to plan future vacations. Also, I used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find my ideal weather condition.

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city on the map.

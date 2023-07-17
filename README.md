# Python API Challenge

## WeatherPy - Project Description 
1. Create a Python script to visualize the weather of over 500 cities of varying distances from the equator.
2. Use citipy Python library and the OpenWeatherMap API to create a representative model of weather across cities.
3. Create a series of scatter plots to showcase the following relationships:
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
4. Complete the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to   0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
5. Create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.
6. Create the following plots:
    - Northern Hemisphere: Temperature vs. Latitude
    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude 
7. After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

## VacationPy - Project Description 
1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition.
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map.

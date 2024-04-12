# python-api-challenge
In this project, I create a Python script to visualize the weather of over 500 cities of varying distances from the equator. The citypy library and OpenWeatherMap API are used together with data munching and problem-solving skills in Python to deliver a representative model of weather across the cities in the first part. In the second part, I use weather data skills to plan future vacations also employing Jupyter notebooks, the geoViews Python library, and the Geoapify API. 

# Tasks in Part I - WeatherPy
1. Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you’ll be utilizing a simple Python library and the OpenWeatherMap API to create a representative model of weather across world cities.

2. Build a series of scatter plots to showcase the following relationships:

3. Temperature (C) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude

4. After each plot added a sentence or two explaining what the code is and analyzing.

5. Ran a linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (C) vs. Latitude 
Southern Hemisphere - Temperature (C) vs. Latitude 
Northern Hemisphere - Humidity (%) vs. Latitude 
Southern Hemisphere - Humidity (%) vs. Latitude 
Northern Hemisphere - Cloudiness (%) vs. Latitude 
Southern Hemisphere - Cloudiness (%) vs. Latitude 
Northern Hemisphere - Wind Speed (m/s) vs. Latitude 
Southern Hemisphere - Wind Speed (m/s) vs. Latitude



# Tasks in Part II - VacationPy
Using hvplots and geoviews and geoapi API:

1. load and the weather data
2. Narrow down the city_data_df DataFrame to find your ideal weather condition
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
6. Narrow down the DataFrame to find your ideal weather condition. For example:
7. Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.



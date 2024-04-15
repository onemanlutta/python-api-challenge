# python-api-challenge

In this project, I create a Python script to visualize the weather of over 500 cities of varying distances from the equator. The citypy library and OpenWeatherMap API are used together with data munching and problem-solving skills in Python to deliver a representative model of weather across the cities in the first part. In the second part, I use weather data skills to plan future vacations also employing Jupyter notebooks, the geoViews Python library, and the Geoapify API. 

# Tasks in Part I - WeatherPy

1. Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
2. Build a series of scatter plots to showcase the following relationships:
3. Temperature (C) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude
4. After each plot added a sentence or two explaining what the code is and analyzing.
5. Ran a linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (C) vs. Latitude

![northern_hemi_lat_vs_max_temp_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/732c7ee3-6f65-47e7-b575-fc6b45d8fd15)

Southern Hemisphere - Temperature (C) vs. Latitude 

![southern_hemi_lat_vs_max_temp_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/f3acbbee-cb52-46df-898a-4565eb88784d)

Northern Hemisphere - Humidity (%) vs. Latitude 

![northern_hemi_lat_vs_humidity_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/1eaa2b8f-a6d1-4f30-8385-fef11425320e)

Southern Hemisphere - Humidity (%) vs. Latitude 

![southern_hemi_lat_vs_humidity_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/a80e6990-a970-471f-abd4-561b1a9b8a97)

Northern Hemisphere - Cloudiness (%) vs. Latitude 

![northern_hemi_lat_vs_cloudiness_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/a8a2f2d6-3892-4c88-8cdd-21267c160be9)

Southern Hemisphere - Cloudiness (%) vs. Latitude 

![southern_hemi_lat_vs_cloudiness_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/470f36a3-1554-4614-8a52-bd38e7be7e62)

Northern Hemisphere - Wind Speed (m/s) vs. Latitude 

![northern_hemi_lat_vs_wind_speed_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/2b423b8c-fd0f-4a6c-9647-3c731b38b20f)

Southern Hemisphere - Wind Speed (m/s) vs. Latitude

![southern_hemi_lat_vs_wind_speed_regression](https://github.com/onemanlutta/python-api-challenge/assets/118937365/9b439e71-e7bb-4a63-ba5a-52712e392973)



# Tasks in Part II - VacationPy

Using hvplots and geoviews and geoapi API:

1. load and the weather data
2. Map all the cities in the DataFrame

![Plot of all cities](https://github.com/onemanlutta/python-api-challenge/assets/118937365/1f0e7846-95ee-45bc-b4d0-6feb9b34f31e)

3. Narrow down the city_data_df DataFrame to find your ideal weather condition
4. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
5. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
6. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

![Plot of selected hotels within the radius of the city](https://github.com/onemanlutta/python-api-challenge/assets/118937365/5362e1b1-9000-4904-8c1c-9454d54186e7)

# The Solutions

These are contained in the Weatherpy folder as Jupyter Notebooks as WeatherPy.ipynb for Task I and as VacationPy.ipynb for Task II. The datasets and analysis outputs are found in the root of the WeatherPy directory as output_data.  



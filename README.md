# Python API: "What's the weather like as we approach the equator?"
-------------------------------------------------------------------


![Equator](Images/Equator_Image.png)

## WeatherPy

##### The objective is to write a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.

The visualizations include a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude 
- Wind Speed (mph) vs. Latitude

##### Run linear regression on each relationship, by separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

The visualizations include a series of scatter plots to showcase the following relationships:

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

#### The script accomplishes the following:

#### 1.

Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.

Performs a weather check on each of the cities using a series of successive API calls.

Includes a print log of each city as it's being processed with the city number and city name.

Saves the data retrieved from API calls into CSV files 

Draw the scatter plots to visualize the relationship between various weather factors

Save the scatter plots into PNG images


#### 2.

Filter the data based on Northern Hemisphere and Southern Hemisphere 

Draw the scatter plots to visualize the relationship between various weather factors both on Northern and Southern Hemisphere

Run the linear regression on each relationship

What the linear regression is analyzing











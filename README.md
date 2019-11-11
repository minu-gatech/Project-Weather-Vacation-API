# Python API: "What's the weather like as we approach the equator?"
-------------------------------------------------------------------


![Equator](Images/Equator_Image.png)

## (Part-1) WeatherPy

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

Analysis of linear regression




## (Part-2) VacationPy

##### The objective is to plan future vacations based on Weather data gathered in  'WeatherPy' part of project. 
- Create a heat map that displays the humidity for every city.
- Use Jupyter gmaps and the Google Places API for this part of project.
- Narrow down the DataFrame to find the ideal weather condition. 
- Use Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.
- Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.









# python-api-challenge

# Weather Analysis and Geospatial Data Visualization

This project explores weather patterns and visualizes geospatial data through API calls. It consists of two main components:

## Part 1: WeatherPy
In this section, we analyze the weather of approximately 600 random cities using API requests. The `WeatherPY.ipynb` Jupyter notebook contains the code for this analysis. Key visualizations include:
- Scatter plots to examine the correlation between latitude and weather attributes (Temperature, Humidity, Cloudiness, Wind Speed).
- Linear regression models for both Northern and Southern Hemispheres to assess the relationship strength between latitude and weather variables.

**Note:** The data reflects live weather conditions; hence, the outputs will vary with each code execution. The discussions in the markdown cells pertain to the data available at the time of analysis.

## Part 2: VacationPy
The `VacationPY.ipynb` Jupyter notebook extends the analysis from Part 1. Using the weather data of cities (sourced from the `cities.csv` in the `output-data` folder), we:
- Create geospatial visualizations on a map.
- Filter cities to identify those matching ideal vacation weather criteria.
- Retrieve and visualize the nearest hotel information for each selected city using API calls.

### Data Sources
The data for this project was retrieved via API calls from:
- OpenWeatherMap: `http://api.openweathermap.org/data/2.5/weather`
- Geoapify: `https://api.geoapify.com/v2/places`


# python-api-challenge

# Weather Analysis and Geospatial Data Visualization

This project explores weather patterns and visualizes geospatial data through API calls. It consists of two main components:

## Part 1: WeatherPy
In this section, I analyzed the weather of approximately 600 random cities using API requests. The `WeatherPY.ipynb` Jupyter notebook contains the code for this analysis. Key visualizations include:
- Scatter plots to examine the correlation between latitude and weather attributes (Temperature, Humidity, Cloudiness, Wind Speed).
- Linear regression models for both Northern and Southern Hemispheres to assess the relationship strength between latitude and weather variables.

**Note:** The data reflects live weather conditions; hence, the outputs will vary with each code execution. The discussions in the markdown cells pertain to the data available at the time of analysis.

## Part 2: VacationPy
The `VacationPY.ipynb` Jupyter notebook extends the analysis from Part 1. Using the weather data of cities (sourced from the `cities.csv` in the `output-data` folder), I:
- Created geospatial visualizations on a map.
- Filtered cities to identify those matching my ideal weather condition for a vacation.
- Retrieved and visualizde the nearest hotel information for each selected city using API calls.

### Data Sources
The data for this project was retrieved via API calls from the following websites:
- OpenWeatherMap: https://openweathermap.org/
- Geoapify: https://www.geoapify.com/


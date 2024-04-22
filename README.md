# python-api-challenge

# Weather Analysis and Geospatial Data Visualization

This project explores weather patterns and visualizes geospatial data through API calls.  It consists of two main components:

## Part 1: WeatherPy
In this section, I analyzed the weather of approximately 600 random cities using API requests. The `WeatherPY.ipynb` Jupyter notebook contains the code for this analysis. Key visualizations include:
- scatter plots to examine the correlation between latitude and weather attributes (Temperature, Humidity, Cloudiness, Wind Speed); and
- linear regression models for both Northern and Southern Hemispheres to assess the relationship strength between latitude and weather variables.

**Note:** The data reflects the weather conditions of random cities at the time of code execution, meaning the outputs may vary with each run. Discussions within the markdown cells are based on the outputs generated during the time of code execution.

## Part 2: VacationPy
The `VacationPY.ipynb` Jupyter notebook extends the analysis from Part 1. Using the weather data of cities (sourced from the `cities.csv` in the `output_data` folder), I:
- created geospatial visualizations on a map ; 
- filtered cities to identify those matching my ideal weather conditions for a vacation; and
- retrieved and visualized the nearest hotel information for each selected city using API calls.

### Prerequisites
Additional libraries may be required in your Jupyter notebook environment for the code to execute successfully. Please ensure the following libraries are installed: hvplot, geoviews, and citipy.

### Data Sources
The data for this project was retrieved via API calls from the following websites:
- OpenWeatherMap: https://openweathermap.org/
- Geoapify: https://www.geoapify.com/

To retrieve data successfully, API keys from the above sources must be included in the `api_keys.py` file.



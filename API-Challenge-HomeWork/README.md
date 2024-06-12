# python-api-challenge
# Repository Setup:
- Created a new repository for the Module 6 challenge titled "python-api-challenge".
- Cloned the new repository.
- Created a local git repository and a directory for the assignments.
- Inside the folder, added the files called api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb from the starter code ZIP file provided.
- Added a .gitignore file to prevent the API keys from being shared with the public.

# Weather Data Analysis (Part 1):

## Requirement 1: Creating Plots to Showcase Weather-Latitude Relationships:
- Utilized the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.
- Created a series of scatter plots to illustrate the relationships between:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed.
## Requirement 2: Computing Linear Regression:
- Separated the plots into Northern Hemisphere (≥ 0° latitude) and Southern Hemisphere (< 0° latitude).
- Created scatter plots for each hemisphere, including the linear regression line, the model's formula, and the r values.
### Plots included:
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude.
- After each pair of plots, explained the modeled linear regression and described noticeable relationships and any other findings.

# Vacation Planning (Part 2):
- Utilized weather data skills to plan future vacations, incorporating Jupyter notebooks, the GeoViews Python library, and the Geoapify API.
- Imported required libraries and loaded the CSV file with weather and coordinates data for each city created in Part 1.
**Created a map displaying a point for every city in the city_data_df DataFrame.**
- Narrowed down the DataFrame to cities meeting criteria: max temp between 250 and 300, wind speed less than 4.5, and zero cloudiness.
**Created a new DataFrame hotel_df to store city, country, coordinates, and humidity.**
- Used the Geoapify API to find the first hotel within 10,000 meters of the coordinates for each city.
- Added the hotel name and country as additional information in the hover message for each city on the map.






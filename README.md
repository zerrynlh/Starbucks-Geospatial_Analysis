# Starbucks Reserve Roastery Location Analysis

This project aims to find the next location for a Starbucks Reserve Roastery in the state of California. The analysis investigates the demographics of various counties in California to determine potentially suitable locations based on specific criteria.

## Objective

The primary objective of this project is to identify suitable locations for a new Starbucks Reserve Roastery based on demographic factors such as population density, median age, and high earners in different counties of California.

## Approach

The project follows these steps:

1. **Data Collection**: 
   - Obtain data on the boundaries of California counties and Starbucks store locations with latitude and longitude information.

2. **Data Preprocessing**:
   - Load and preprocess the county boundaries data using Geopandas.
   - Filter Starbucks store data to include only the necessary information.

3. **Spatial Analysis**:
   - Perform a spatial join between Starbucks store locations and county boundaries to associate each store with its respective county.
   - Analyze demographic data of California counties, including population density, median age, and high earners.

4. **Location Selection**:
   - Apply specific criteria to filter candidate counties that are potentially suitable for a new Starbucks Reserve Roastery.

5. **Visualization**:
   - Visualize the selected candidate counties on a map using Folium.
  
To view the interactive maps, download the HTML file for map1 from [here](https://github.com/zerrynlh/Starbucks-Geospatial_Analysis/blob/main/map1.html) and map2 [here](https://github.com/zerrynlh/Starbucks-Geospatial_Analysis/blob/main/map2.html). The files can be opened in a web browser.


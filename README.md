# World_Weather_Analysis

## Overview

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they've recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data.
For this challenge, you will use the weather description data you've already retrieved in this module to enhance the PlanMyTrip app. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. The beta tester will choose four cities from the list of potential travel destinations to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities and a marker layer map.

* Deliverable 1: Retrieve Weather Data
* Deliverable 2: Create a Customer Travel Destinations Map
* Deliverable 3: Create a Travel Itinerary Map

## Retrieve Weather Data 

* Retrieve all of the following information from the API call:
   - Latitude and longitude
   - Maximum temperature
   - Percent humidity
   - Percent cloudiness
   - Wind speed
   - Weather description (for example, clouds, fog, light rain, clear sky)

* Add the weather data to a new DataFrame 
* Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder 

## Create a Customer Travel Destinations Map

* Input statements are written to prompt the customer for their minimum and maximum temperature preferences. 
* A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
* The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
* The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.
* A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
   - Hotel name
   - City
   - Country
   - Current weather description with the maximum temperature

* The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png.

![WeatherPy_vation_map](https://github.com/cbrito3/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vation_map.png)

## Create a Travel Itinerary Map 

* Four DataFrames are created, one for each city on the itinerary. 
* The latitude and longitude pairs for each of the four cities are retrieved. 
* A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. 
* A DataFrame that contains the four cities on the itinerary is created. 
* A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information: 
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature
    
   ![WeatherPy_travel_map_markers](https://github.com/cbrito3/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

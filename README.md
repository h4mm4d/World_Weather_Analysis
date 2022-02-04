# World_Weather_Analysis
## Overview 
This analysis to map cities with certain temperature range that can help plan a road trip for a client. This assignment utilized Pyhton, Panda and APIs. Over 700 cities all over the world were analyzed for following weather data.
- Temperature
- Cloudiness 
- Windspeed 
- Humidity and
- Current Weather Description
Based on those criteria, it was a smaller subset of cities were selected that met certain weather conditions. Then those cities were mapped and then cities were selected and drive was mapped. 
## Results 
It was a three-step process:
### 1. Building and Weather Database 
A set of 2000 random coordinates were taken that produces 772 cities (as about 71% coordinated end up in the water) then it was placed on a CSV file to analyze.
### 2. Building a List of Cities with Hotel and mapping it
In this step the database from previous task was cleaned, assigned hotels and then mapped on Google Maps. This brought down number of cities to 169. 
![Vacation Search map](https://raw.githubusercontent.com/h4mm4d/World_Weather_Analysis/main/Vacation_Search/WeatherPy_vacation_map.png)
### 3. Planning the road trip
Here four cities were selected where a road trip by driving was possible. Then proper driving path was mapped. The results are as below. 
![Travel Map](https://github.com/h4mm4d/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png?raw=true)
![Travel Cities with Markers](https://github.com/h4mm4d/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png?raw=true)

# World_Weather_Analysis

## Overview of the School District Analysis
The purpose of this analysis was to use our skills with using API calls in Python notebooks. We generated a list of 2000 random latitudes and longitudes using the random function which was fed into the citipy module to retrieve the nearest city to the set of latitudes and longitudes. After retrieving the city names, we used the OpenWeatherMap API to obtain the weather details for these cities. With this city list and weather info, we used the Google Nearby places API to obtain hotels in these cities.

The goal was to create an itinerary for the user after they input the min and max temperatures to determine locations which are suitable for a vacation. After identifying the cities which suit the user preferences, the goal was to create a travel itinerary showing the route between the different cities along with the marker layer indicating the hotel and the weather conditions in those cities. For this assignment, I chose 4 cities in Australia to plan the vacation based on the temperature range as min:70 degrees and max:80 degrees.

## Results

### Vacation Search

#### This image below shows the map with the city options along with the hotel details

![Vacation_Search_Map](https://github.com/dkatragadda/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary 

#### This image below shows the map with the travel route between the cities chosen for the vacation

![Vacation_Travel_Map](https://github.com/dkatragadda/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

#### This image below shows the map with the marker layer for the cities chosen for the vacation

![Vacation_Travel_Map_Markers](https://github.com/dkatragadda/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

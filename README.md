# World_Weather_Analysis

## Purpose
The purpose of this project was to create an algorithm that allows customers to find ideal vacation spots within their a specified temperature range. Customers input their preferences, and the code outputs a possible itinerary and directions and weather descriptions about the chosen locations. 

## Resources
- Google Maps APIs (Places and Directions) 
- Open Weather API
- Citipy module
- Jupyter Notebook

## Approach Outline
- Random coordinates are generated and coordinates belonging to cities are associated using the Citipy module
- For each city, current local weather is scraped using the OpenWeatherAPI
- Customers filter on the cities based on their ideal temperature and are given a world map of potential travel destinations
 <img width="1128" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/10199828/128401099-c093251f-075b-473d-91fa-7da597d0f3aa.png">
- Next, local hotels for each destination are found using the Google Places API  
- Lastly, a sample itinerary and travel route is provided for 4 cities using the Google Directions API. We also generate maps that display current local weather. <img width="1118" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/10199828/128401733-d6e420d1-a4ce-482b-a130-20605b6f6c92.png">
<img width="1114" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/10199828/128401950-6384ff87-366b-4047-bb15-5b34b4b8af51.png">

# Weather Analysis and Vacation Planning with Google API
## Overview
This project uses Python libraries and the Google API to generate a vacation itinerary based off real-time weather data. First, a list of random cities and their weather data is filtered based off temperature criteria set by the user. For each city on this list, a hotel nearest the city’s geographical center is recorded. The user may then specify up to four of the potential destinations and a driving route layer map will be generated, complete with interactive markers that show hotel information when selected. 
## Results
Weather data is pulled from two thousand randomly generated cities and filtered by average temperature (range: 75-90):

<img src="https://github.com/pojones/World_Weather_Analysis/blob/d00456f0eea1562401dd04dd1f2fae0a26be6376/WeatherPy_vacation_map.png" size=35%>

The four cities selected for a potential roadtrip [Westport, Yarmouth, Norfolk, Palmer] and the driving route are shown here:
<br/><br/>
![](https://github.com/pojones/World_Weather_Analysis/blob/f3a9fb0997b8c597aba433bd340b27a2222374cc/Vacation_Search/WeatherPy_travel_map.png)
<br/><br/>
Hotel and current weather information are displayed for each destination:
<br/><br/>
![](https://github.com/pojones/World_Weather_Analysis/blob/f3a9fb0997b8c597aba433bd340b27a2222374cc/Vacation_Search/WeatherPy_travel_map_markers.png)

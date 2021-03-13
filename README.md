# Python-API-challenge 
## Overview: ## 
With successive API calls, city's weather is retrieved and then cities are narrowed down with ideal conditions for vacation. The heatmap is created with pins showing hotels near the vacation spots.

## Final Report ##
### Part I: ### 
> The weather of 500+ cities across the world of varying distance from the equator is retreived with API calls to OpenWeatherAPI. Various graphs are plotted between latitude and other factors like temperature, humidity, cloudiness and wind speed. Linear regression is also plotted between latitude and the factors and their relationships are analysed. 
### Part II: ###
> - The cities retrieved from part I are then used to create a heatmap that displays humidity for every city. <br>
> - Cities with ideal conditions like: temperature between 70 and 80, zero cloudiness and wind speed less than 10mph are filtered. <br>
> - Google Places API is used to find the first hotel for each city located within 5000 meters of its coordinates. <br>
> - The hotel name is plotted on top of the humidity heatmap with each pin containing the `Hotel Name`, `City`, and `Country`.

## Observations: ##
> - With the increase in latitude(that is., above equator), the maximum temperature in the cities are getting reduced. There is strong relationship between Latitude and maximum Temperature in the region.
> - When it comes to humidity, the cities in southern hemisphere are more correlated to latitude than the cities in northern hemisphere.
> - The correlation between latitude and cloudiness/wind speed is very little to none.

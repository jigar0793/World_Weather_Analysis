# World_Weather_Analysis

## Overview of the analysis

In this project we are going to use OpenWeatherMap and Google APIs to create a Map by taking input from the user about their temperature preferences and providing them a heatmap with potential vacation destinations within their preferred temperature ranges, which provides them with name and location of the city, the country, description of the weather, and their most recent exact temperature values.

## Purpose

The purpose of this project is to write code for an app, called, PlanMyTrip, which will allow users to add their weather preferences, and get access to potential travel destinations and nearby hotels. There is also a feature that creates best routes between multiple chosen destinations on a map.

## Results
    The project is split up into three parts:

In the Weather_Database folder, I created a DataFrame with travel destinations using latitute and longitude, along with other information, from the OpenWeatherMap API. This DataFrame will be used to select travel destinations based of weather preferences by the users.

In the Vacation_Search folder, I created a map with travel destinations based on the weather preferences of the user, using the DataFrame created during the previous step of the project. A description of the current weather at locations, along with other information is provided on google maps when markers for different relevant cities are clicked on.

In this last part of the project, stored in the Vacation_Itinerary folder, I used the Google Directions API to create a travel itinerary tha shows the route between four cities chosen from the user's possible travel destinations. Similiar to the last step, this map also contains markers with relevant information for each city.

## Summary

Through the use of APIs, this project successfully identifies cities by using latitude and longitude, and based on weather preferences of the user, filters out cities as travel destinations. The travel itinerary is an experimental step and can be made more robust by allowing the user to choose cities they want to make an itinerary out of, rather than me choosing them. Overall, the project succeeds to achieve its' goals.

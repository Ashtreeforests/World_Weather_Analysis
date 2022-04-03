# World_Weather_Analysis

## Overview

Analysis of how weather conditions include travel and tourism. Collected and analyzed weather data across cities worldwide using the below resources. Goal is to be able to provide worldwide travelers a tool to enable them to determine travel destinations based on weather conditions.

## Resources

* CSV Files: Weather_Database.csv, WeatherPy_vacation.csv

* Jupyter Notebook Files: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

* Tools: Python v3.10, Pandas, Matplotlib, JSON

## Weather Database

A random set of 2,000 latitudes and longitudes were generated. An API key was made on current weather data for the nearest corresponding cities.

API Key Data:

* Latitude and longitude
* Maximum temperature 
* Percent humidity
* Percent cloudiness
* Wind speed
* Current Weather description

## Vacation Search

Travelers can search for nearby hotels with general weather description at each city as shown below. 

## Sample Travel Destinations
![image](https://user-images.githubusercontent.com/96931376/161446902-02e687a4-c763-4845-92b1-0e0eb31ef3ef.png)

## Vacation Itinerary

Travelers can generate an itinerary route as shown below. 

![image](https://user-images.githubusercontent.com/96931376/161446961-3729997d-90a2-4779-aef6-d7169ff2520a.png)

## Statistical Analysis

Global city data was plotted by latitude with linear regression used to find the relationship between the following variables:

* Latitude and Maximum Temperature
* Latitude and Humidity
* Latitude and Cloudiness
* Latitude and Wind Speed

## Scatter Plots based on Latitude

![image](https://user-images.githubusercontent.com/96931376/161447058-89d059be-cd92-4c81-8843-fc1a7f2c4ab3.png)
![image](https://user-images.githubusercontent.com/96931376/161447062-1f254bbf-56e7-41f1-9e5e-77afedeeb9f1.png)
![image](https://user-images.githubusercontent.com/96931376/161447068-4db0fd9f-90b9-457f-8b2f-d522ebd6b960.png)
![image](https://user-images.githubusercontent.com/96931376/161447073-54faa4c5-e16f-461e-9b41-03c932ee4525.png)

## Linear Regression on the Northern and Southern Hemispheres

All four weather parameters: 

* Maximum temperature
* Humidity
* Cloudiness
* Wind speed.

Maximum Temperature

![image](https://user-images.githubusercontent.com/96931376/161447123-97a83068-70e1-4b8c-a54b-fba7cafff6a2.png)

![image](https://user-images.githubusercontent.com/96931376/161447134-ae047d6d-51a9-402e-a3a9-fa9b8a5e1a0d.png)

Percent Humidity

![image](https://user-images.githubusercontent.com/96931376/161447203-3753f182-2024-4167-83af-6f062b1d767c.png)

![image](https://user-images.githubusercontent.com/96931376/161447210-b8f039ff-f258-471e-9a34-93096f97de62.png)

Percent Cloudiness

![image](https://user-images.githubusercontent.com/96931376/161447252-1f12213b-39e3-46a0-817f-50077f08b71f.png)

![image](https://user-images.githubusercontent.com/96931376/161447258-181c03cd-aa88-4320-81fc-dff4ac2544c9.png)

Wind Speed

![image](https://user-images.githubusercontent.com/96931376/161447293-ef59084e-86ca-419d-944a-b9b34c84ea96.png)

![image](https://user-images.githubusercontent.com/96931376/161447302-a33e740d-0791-4874-baeb-24efe8693410.png)



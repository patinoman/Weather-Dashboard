# **Weather Dashboard**

A simple weather dashboard app to display a 5-day weather forecast for any city in the world

## Description

---

In this repository I created a simple weather application that allows the user to search a city and in return: receive the temperature, humidity, wind speed, and UV index for that city in the current day. This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery/Bootstrap, and makes use of a server-side API Open Weather Map to fetch the info.

The application is generated using the following acceptance criteria:

- GIVEN a weather dashboard with form inputs
- WHEN I search for a city
- THEN I am presented with current and future conditions for that city and that city is added to the search history
- WHEN I view current weather conditions for that city
- THEN I am presented with the city name, the date, an icon representation of weather conditions, the - temperature, the humidity, the wind speed, and the UV index
- WHEN I view the UV index
- THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
- WHEN I view future weather conditions for that city
- THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
- WHEN I click on a city in the search history
- THEN I am again presented with current and future conditions for that city

## Process

---

I linked Bootstrap and jQuery to my index.html starter code. I faced many challenges while finishing the code for this particular project, mostly due to configuring the code to accurately fetch all the API info for the criteria (Temp, Humidity, Wind Speed, UV Index).

## Credits

---

My friend Jesse and Jose, who have assisting me through my progress and many many MANY struggles.

- https://stackoverflow.com/questions/9775375/parseint-with-jquery
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split
- https://getbootstrap.com/docs/4.4/layout/overview/
- https://openweathermap.org/api

## Screenshot

---

![Weather Dashboard](/assets/images/weather-dashboard.png?raw=true "Weather dashboard render")

## Links

---

https://patinoman.github.io/weather-dashboard/

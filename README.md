
# Clima Agora - Weather App

This is a JavaScript weather application that uses the OpenWeather API to fetch weather data and display it for a given city. It includes features such as displaying temperature, wind speed, humidity, weather description, and a weather icon. Users can also choose from a list of suggested cities or search for any city by name.

## Project Overview

The application allows users to:

    - Input a city name and get real-time weather data.
    - View temperature, humidity, wind speed, and weather description.
    - See a background image of the city based on the weather.
    - Get suggestions for popular cities to view the weather.

## Features

- City Search: Users can search for a city by typing its name in an input field.
- Weather Data Display: Displays temperature, weather description, humidity, and wind speed.
- City Suggestions: The app offers a list of popular cities like Vienna, Vancouver, and others to click on for quick access to weather information.
- Background Image Change: The background image of the page changes to a relevant image based on the city being viewed, fetched from Unsplash.
- Error Handling: Displays an error message if the city is not found.
## Tech Stack

**HTML**: For structuring the web page.
**CSS**: For styling the page and making it visually appealing.
**JavaScript**: For fetching weather data from the OpenWeather API and managing user interactions.
**OpenWeather API**: To fetch real-time weather data.
**Unsplash API**: To fetch city-specific images for the background.
## Code Explanation

**HTML**: Contains the structure of the app, including input fields for city names and a container for displaying weather data.

**CSS**: The style.css file handles the styling, including responsive design and background changes.

**JavaScript**:

    - Fetches weather data from the OpenWeather API.
    - Displays the results dynamically based on user input or selected city.
    - Updates the background using Unsplash API based on the city name.

## JavaScript Logic

1. Fetching Weather Data: The getWeatherData() function fetches weather data from OpenWeather API using the city name.
2. Displaying Weather: The showWeatherData() function updates the page with the fetched weather data, including temperature, wind speed, and humidity.
3. Error Handling: If the city is not found, an error message is displayed.
4. Background Image: The background of the page is dynamically changed using a relevant city image from Unsplash.
## Screenshots

![London](https://iili.io/FA0A691.png)
![Blumenau](https://iili.io/FA0Ar8P.png)

## License

This project is for educational purposes and is open to use or modify as needed.

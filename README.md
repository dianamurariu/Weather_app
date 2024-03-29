# Weather App

Welcome to the Weather App! This simple web application provides real-time weather information for various cities. The app is built using HTML, Bootstrap and JavaScript. It utilizes the Open Weather API to fetch weather data and stores city information in JSON file.

## Live Demo

Check out the live demo of the Weather App [here](https://dianamurariu.github.io/Weather_app/).

## Features

- Display of essential weather information for a selected city:
  - City Name
  - Temperature in Celsius
  - Weather Type
  - Time
  - Date
  - Wind Speed
  - Humidity
  - Atmospheric Pressure

## City Information

The app stores city information in a JSON file named cities.json. To add or update city information, modify this file accordingly. Each city object should follow the structure below:

Example:
{
"id": 1,
"name": "City Name",
"latitude": 40.7128,
"longitude": -74.0060
}

## API Integration

The app utilizes the Open Weather API to fetch real-time weather data. The API key is obtain by signing up on the Open Weather Map website and replacing the placeholder in the script.js file with the actual API key.

## Dependencies

- [Bootstrap](https://getbootstrap.com/): Used for styling the UI and making it responsive.
- [Open Weather API](https://openweathermap.org/): Provides real-time weather data.

## Usage

1. Clone the repository.
2. Open the `index.html` file in your preferred web browser.

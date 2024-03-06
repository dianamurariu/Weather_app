# Weather App

Welcome to the Weather App! This simple web application provides real-time weather information for various cities. The app is built using HTML, Bootstrap and JavaScript. It utilizes the Open Weather API to fetch weather data and stores city information in JSON file.

## Table of Contents

- [Features](#features)
- [Live Demo](#live-demo)
- [Project Structure](#project-structure)
- [City Information](#city-information)
- [API Integration](#api-integration)
- [Usage](#usage)
- [Dependencies](#dependencies)

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

## Live Demo

Check out the live demo of the Weather App [here](https://dianamurariu.github.io/Weather_app/).

## Project Structure

- index.html: The main HTML file that displays the weather information.
- styles.css: Custom styles for the app.
- script.js: JavaScript file responsible for fetching weather data and updating the UI.
- cities.json: JSON file containing information about cities.

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

const key = '7fb35c18c62511d6b460ef5313a52f16';

## Usage

1. Clone the repository.
2. Open the `index.html` file in your preferred web browser.

## Dependencies

- [Bootstrap](https://getbootstrap.com/): Used for styling the UI and making it responsive.
- [Open Weather API](https://openweathermap.org/): Provides real-time weather data.

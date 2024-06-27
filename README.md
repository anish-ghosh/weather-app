# Weather App

This is a simple weather application that fetches and displays the current weather information for a given city using the OpenWeatherMap API.

## Features

- Search for current weather by city name
- Display temperature, humidity, and wind speed
- Display appropriate weather icon based on the current weather condition

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Getting Started

### Prerequisites

To run this project, you need a modern web browser. No additional software is required.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd weather-app
    ```

### Usage

1. Open the `index.html` file in your web browser.
2. Enter the name of the city you want to check the weather for in the input field.
3. Click the search button to fetch and display the weather information.

### OpenWeatherMap API Key

This project uses the OpenWeatherMap API to fetch weather data. You will need to provide your own API key.

1. Sign up for an API key at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Replace the `apiKey` variable in the `index.html` file with your API key:
    ```javascript
    const apiKey = "your-api-key-here";
    ```

## File Structure

```plaintext
weather-app/
│
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
│
├── style.css
│
└── index.html


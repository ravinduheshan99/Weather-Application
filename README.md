
# Live Weather Application Using HTML CSS and JS

Welcome to the Live Weather Application! This project is a simple and intuitive web application developed using plain HTML, CSS, and JavaScript. It allows users to get real-time weather information for any location they enter.


## Acknowledgements
I would like to express my gratitude to the following resources and individuals who contributed to the development of this Live Weather Application
 - [OpenWeatherMap API](https://openweathermap.org/current)-For providing the weather data used in this application.
 - [MDN Web Docs](https://developer.mozilla.org/en-US/)-For the comprehensive documentation and tutorials on HTML, CSS, and JavaScript that greatly assisted in the development process.

## Demo
![demo](https://github.com/ravinduheshan99/Weather-Application/blob/main/assets/videos/demo.gif)

## Features

**Real-time Weather Data:** Fetches current weather information based on the user's input location.

#### Weather Details
- **Weather Type:** Displays the current weather condition (e.g., Clear, Rain, Snow, Clouds, Mist, Haze).
- **Temperature:** Shows the temperature in Celsius.
- **Humidity:** Provides the current humidity level.
- **Wind Speed:** Indicates the current wind speed.
**Error Handling:** If the user enters an invalid location, an error message is displayed stating "Location not found".


## API Reference

#### Get weather by city name

```http
  https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=${APIKey}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `c6b88ec3fb8b77f4488c1356ce494d45` | `string` | **Required**. City name to fetch |


## Deployment

- Enter your desired location into the input field visible on the screen.

- Click the Search button.

- The application will display the current weather information for the entered location.

- If an invalid location is entered, an error message will be shown.


## Authors

- [@ravinduheshan99](https://github.com/ravinduheshan99)


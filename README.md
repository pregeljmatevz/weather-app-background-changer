# weather-app-background-changer
A weather app that updates the background based on real-time weather conditions using the OpenWeatherMap API

A weather app that fetches weather data using the OpenWeatherMap API and changes the background based on current weather conditions.

## Features

- Fetches real-time weather data from OpenWeatherMap API.
- Dynamically changes background images based on weather conditions.
- Displays temperature, pressure, humidity, wind speed, sunrise, and sunset times.

## Demo

![Weather Background Changer Demo](https://github.com/pregeljmatevz/weather-app-background-changer/assets/64079472/08ed2f28-6fbc-4f62-a427-7e572d2a42f7)


## Getting Started

### Prerequisites

- A web browser
- Internet connection
- An API key from OpenWeatherMap

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-background-changer.git
    ```

2. Navigate to the project directory:
    ```bash
    cd weather-background-changer
    ```

3. Open `index.html` in your web browser to view the app.

### Usage

1. Obtain an API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

2. Replace the `apiKey` variable in the `getWeather` function within the `index.html` file with your own API key:
    ```javascript
    var apiKey = 'your_api_key_here';
    ```

3. Enter a city name and click the "Get Weather" button to fetch and display the weather information and corresponding background.

## Backgrounds

The app changes the background based on the following weather conditions:

- Clear Day: `backgrounds/clear-day.png`
- Clear Night: `backgrounds/clear-night.png`
- Mist Day: `backgrounds/mist-day.png`
- Mist Night: `backgrounds/mist-night.png`
- Rain Day: `backgrounds/rain-day.png`
- Rain Night: `backgrounds/rain-night.png`
- Snow Day: `backgrounds/snow-day.png`
- Snow Night: `backgrounds/snow-night.png`
- Sunset: `backgrounds/sunset.png`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API.
- [Bootstrap](https://getbootstrap.com/) for the responsive design framework.

# Weather App

A JavaScript weather lookup exercise using the wttr.in JSON endpoint.

## Features

- Search for a city.
- Display temperature in Celsius, weather conditions and humidity.
- Keep recent searches in browser local storage.
- Show an error message when weather data cannot be loaded.

## Run

```bash
git clone https://github.com/sangeethareddy9/frontend-weather.git
cd frontend-weather
```

Open `index.html` in your browser, enter a city and select **Get Weather**. Internet access is required.

## Implementation

All code is in [index.html](index.html). It uses `fetch`, `async/await`, JSON parsing, DOM updates and local storage.

The request follows `https://wttr.in/<city>?format=j1`. Data availability depends on that external service. The current layout uses a fixed-width card; further mobile-layout work is a possible improvement.

## Author

[Sangeetha Chirla](https://github.com/sangeethareddy9)

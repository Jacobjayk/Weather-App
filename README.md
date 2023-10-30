# Weather App In React Native

A simple Android app that shows you the current weather and forecast for any location in the world. It uses the OpenWeather API to fetch the weather data and displays it in a simple and beautiful user interface. The app is designed to be easy to use, fast, and reliable.

### Installing

> Clone This Repo

> Run npm install

> TODO

> Run The App

## TODO

- Go To https://openweathermap.org/api To Get An API KEY

- Replace This Line ( App.js - Line : 42 )

```javascript
fetch(
  'https://samples.openweathermap.org/data/2.5/weather?q=London,uk&appid=***********************',
);
```

- With ( Replace The Stars With Your API KEY )

```javascript
fetch(
  'http://api.openweathermap.org/data/2.5/weather?q=' +
    this.state.city +
    '&appid=***',
);
```

## Built With

- React Native
- React-Native-Vector-Icons
- OpeanWeatherMap

## Tutorial To Get API KEY

[OpneWeatherMap API KEY]

## Sample Preview

<img src="https://github.com/Jacobjayk/Weather-App/assets/98883398/e4c02439-5ec7-40cc-adcb-d27e71989ebc" width="250" height="500">

## Authors

- **Jacob Akotuah** - _All Works_ - [Jacobjayk](https://github.com/Jacobjayk)

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

# vue-weather-dashboard

Vue Weather Dashboard is a Vue.js application for tracking daily and weekly weather forecasts for selected cities or the user's current location. It provides detailed information on temperature, UV index, wind speed, pressure, and humidity.

Technologies:
- Built using the Vue.js framework
- Utilizes the OpenWeatherMap API for global forecasts and historical data
- Implements interesting Vue2 and Vue3 features, along with VueUse, including reactive dark mode
- Axios is used for API calls
- Reusable Vue components, KeepAlive and VueRouter are employed

Deployment:
The application is deployed on Netlify and is currently available for use by all users.

## Project setup

## Environment Variables

Before running the application, make sure to create a `.env` file in the root directory of the project. Define the following environment variables in the `.env` file:

1. Clone the repository.
2. Create a `.env` file in the root directory of the project.
3. Define the `VUE_APP_WEATHER_API_KEY` variable in the `.env` file with your OpenWeatherMap API key.

## Install dependencies with
```
npm install
```

### Run the application with
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

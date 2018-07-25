# Weather Company Data API access for IBM Cloud

This project shows how to build a basic data access application that continuously runs in the background, processing a variety of weather data from the Weather Company Data for IBM Bluemix REST API endpoints, including severe weather alerts, tropical storm forecasts, and the daily weather almanac to find conditions over time.

## Obtain a Weather Company API Key

If you're participating in the 2018 Call for Code initiative, go the the [special Call for Code Weather web site](https://callforcode.weather.com/) and [register](https://callforcode.weather.com/register). A time-limited API key will be sent to you via email.

All others, sign up for [IBM Cloud here](https://console.bluemix.net/), and provision the free [Weather Company Data plan here](https://console.bluemix.net/catalog/services/weather-company-data).  

## Getting Started in IBM Cloud

Deploy this application to IBM Cloud.

[![Deploy to IBM Cloud](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/codait-advocates/weather-api-nodejs.git)

## Getting Started on localhost

This application can also be run locally. Use this command:

`WEATHER_API_KEY=yourkeygoeshere node app.js`



## License

This code is licensed under Apache 2.0. Full license text is available in [LICENSE](https://github.com/Call-for-Code/weather-api-nodejs/tree/master/LICENSE).

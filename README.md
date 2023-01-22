# Weather web application

This is a [weather web application](https://weather-api-livid-omega.vercel.app/) using [Next.js](https://nextjs.org/) framework bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).



## Screenshot

![screen shot](/public/Screenshot.png)



## Description

This application provides a feature for users to easily search and view the weather conditions of a particular location by simply entering the city name. Utilizing the OpenWeatherMap API, the program retrieves weather data and presents it to the user. The background image and the icons next to the current temprature of the application changes according to the weather conditions.



## Features

- ![#1589F0]Search for weather conditions by city name

- ![#1589F0]Displays location icon and city name that was inputed under form field

-![#1589F0] Displays current weather conditions including current temprature under city name, the human perception of weather like as "Feels like" in °C, minimal currently observed temperature as "Lowest" in °C, and maximal currently observed temperature as "Highest" in °C

- Displays wind gust "Wind Gust" in m/s as only when there is a data

- Changes background image according to the weather conditions

- Displays a default background image when no background image corresponds to the weather description

- Changes background icon according to the weather conditions

- Displays a default icon next to the current temprature when no icon corresponds to the weather description

- Returns the message; "Please enter a valid location" when the city name inputed doesn't exist



## Link to API used
[OpenWeatherMap](https://openweathermap.org/)
This project is using [Current weather data](https://openweathermap.org/current), one of professional collections OpenWeatherMap provides.

It accesses current weather data for any location on Earth including over 200,000 cities. They collect and process weather data from different sources such as global and local weather models, satellites, radars and a vast network of weather stations. Data is available in JSON, XML, or HTML format.



## Tools/Languages used

- Next.js: A framework for building React applications

- OpenWeatherMap API: An API for fetching weather data

- React: A JavaScript library for building user interfaces

- axios: A JavaScript library for handling HTTP requests

- CSS: A stylesheet language for describing the presentation of a document written in HTML

- HTML: A markup language for creating web pages

- JavaScript: A programming language used for creating interactive and dynamic websites.



## Getting started

- 1. Clone the repository:
git clone [weather web application GitHub repository](https://github.com/Kinakopan/weather_API.git)

- 2. Install the dependencies:
```
npm install
```

- 3. Create an account on [OpenWeatherMap](https://openweathermap.org/) to get an API key

- 4. Replace the placeholder API key in the code with your own API key

- 5. Start the development server:
```
npm run dev
```

- 6. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

- 7. Type a location in the input field and press enter to see the weather of that location.

- 8. You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.



## GitHub

Your feedback and contributions are welcome at [weather web application GitHub repository](https://github.com/Kinakopan/weather_API)!



## Author

[Mio Takagi/Kinakopan]



## License

This project is licensed under the MIT License - see the LICENSE file for details.

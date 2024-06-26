
Title:WeatherApp
---------------------------------------------------------------------------------------------------------------------------------
Intern Info
Name:Akhila Vardolu
ID:ICOD7061
---------------------------------------------------------------------------------------------------------------------------------
Introduction
The WeatherApp is a simple React application that allows users to search for weather information based on a city name. It fetches data from the OpenWeatherMap API and displays relevant weather details such as temperature, humidity, wind speed, and weather condition.
---------------------------------------------------------------------------------------------------------------------------------
Implementation
The WeatherApp is implemented using ReactJS. It utilizes useState hook for managing state and fetches weather data asynchronously from the OpenWeatherMap API.
---------------------------------------------------------------------------------------------------------------------------------
Code Explanation
- The WeatherApp component is defined as a functional component using the arrow function syntax.
- It imports necessary React hooks and component styles.
- The component state is managed using the useState hook, specifically for dynamically changing weather icons.
- The `search` function is defined to handle user input and fetch weather data based on the entered city name.
- Weather data fetched from the API is then displayed in the UI.
- Different weather condition icons are displayed based on the weather data received from the API.
---------------------------------------------------------------------------------------------------------------------------------
Functionality
- Users can input a city name in the search bar and click on the search icon to fetch weather information for that city.
- Weather information displayed includes temperature, humidity, wind speed, and a corresponding weather condition icon.
---------------------------------------------------------------------------------------------------------------------------------
Usage
1. Enter the name of the city for which you want to check the weather in the search bar.
2. Click on the search icon.
3. Weather information for the entered city will be displayed.
---------------------------------------------------------------------------------------------------------------------------------
Conclusion
The WeatherApp provides a simple and user-friendly interface for checking weather information. It demonstrates the use of React hooks for managing state and making asynchronous API calls to fetch data. Further improvements can be made to enhance the UI/UX and add additional features such as forecasting and location-based weather updates.

---------------------------------------------------------------------------------------------------------------------------------


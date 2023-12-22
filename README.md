# Umbrella Tech AI Coding Challenge

## 🌞 Description

In this coding challenge you will need to implement a REST API microservice using Java/Kotlin and Spring Boot.

This API will expose 3 endpoints:

1. An endpoint which will return the current sunlight's Kelvin color temperature at given latitude and longitude coordinates.
This will take as input two numeric parameters: latitude and longitude and will output a single numeric value, the color temperature (a value between 2700 and 6000).
2. An endpoint which will return a short poem generated by ChatGPT fitting a theme based on the sun's current position (sunrise, daylight, sunset, moonlight) at given latitude and longitude coordinates.
This will take as input two numeric parameters: latitude and longitude and will output a single string value, the poem generated by ChatGPT.
Here are some examples:
   - 🌅 Sunrise
     ```
     In the stillness of the dawn's embrace,
     A symphony of colors begins to trace.
     The horizon blushes with hues untold,
     As whispers of morning unfold.
     ...
   - 🎑 Moonlight
     ```
     In the velvet cloak of night, a silver ballet,
     The moonlight pirouettes, casting dreams astray.
     A cosmic dancer in the celestial play,
     Brushing darkness with a luminous array.
     ...
3. An endpoint which will list all of the previous requests and responses sent to the API.
This endpoint will not have any input parameters, and will output a list of objects, each containing: request latitude and longitude, request timestamp and the response that was returned to the user.

To achieve #1 and #2, you will need to integrate the following API, which will return you the sunrise and sunset times based at the given coordinates.
You do not need to pass it a specific date, you can use the current day's values which are returned by the API.
https://sunrise-sunset.org/api

You can follow the below diagram in order to calculate the sunlight's Kelvin color temperature:
![fig1](https://github.com/Umbrella-Tech-Solutions/Coding-Challenge/assets/58591785/5fc1d900-e224-4c96-a212-9a3ea47ea39b)

To achieve #3, you will need to store the request parameters, timestamp and response in a SQL database of your choice.

## ☑️ Requirements

- Use Java or Kotlin as the main programming language
- Use Spring Boot as the application framework
- You may use any available libraries for your implementation
- Implement the REST API described above with the 3 endpoints
- Provide documentation on how to build, run and test your application locally (fill in "How to run" section below)

## ⭐ Bonus points (optional)

- Use Kotlin as primary languange
- Containerize your application using Docker
- Implement any form of authentication for the API
- Any creative ideas or enhancements you come up with

## 🛠 How to run
TODO

✨ **Good luck!** ✨

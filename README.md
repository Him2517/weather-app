# weather-app
Weather App with Python and Tkinter

This weather app allows users to input a city name and receive the current weather conditions, including temperature, wind speed, humidity, description, and pressure. It uses the OpenWeatherMap API to fetch the weather data and the timezonefinder library to determine the local time.

## Step-by-Step Explanation

### 1. Importing Necessary Libraries

- We import the necessary libraries for building the graphical user interface (GUI) using Tkinter, handling geographical data with geopy, displaying messages with messagebox, finding timezones with timezonefinder, working with dates and times with datetime, making API requests with requests, and handling timezones with pytz.

### 2. Setting Up the Main Window

- We create the main application window using Tk() and set its title to "Weather App".
- We specify the window's geometry, which is its size and position on the screen. In this case, it's 900 pixels wide, 500 pixels high, and positioned 300 pixels from the left and 200 pixels from the top of the screen.
- We disable the window's ability to be resized by setting `resizable(False, False)`.

### 3. Defining the `getWeather` Function

# Weather App

A Python-based weather application with a graphical user interface built using Tkinter. This app allows users to get current weather information for any city worldwide.

## Features

- Real-time weather data retrieval using OpenWeatherMap API
- Display of current local time for the searched city
- User-friendly interface with intuitive design
- Weather information includes:
  - Temperature
  - Weather condition
  - Wind speed
  - Humidity
  - Weather description
  - Atmospheric pressure

## Prerequisites

Before running this application, ensure you have the following installed:

- Python 3.x
- tkinter
- geopy
- timezonefinder
- requests
- pytz

You can install the required packages using pip:
`pip install tkinter geopy timezonefinder requests pytz`

## Setup

1. Clone this repository or download the source code.
2. Replace `{your_api_key}` in the code with your actual OpenWeatherMap API key.
3. Ensure all image files (`search.png`, `search_icon.png`, `logo.png`, `box.png`) are in the same directory as the script.

## Usage

1. Run the script:
   `python weather_app.py`
2. Enter a city name in the search box.
3. Press Enter or click the search icon to get the weather information.

## How It Works

1. **User Input**: The user enters a city name in the search box.

2. **Geolocation**: Using the `geopy` library, the app retrieves the latitude and longitude of the entered city.

3. **Time Zone**: The `timezonefinder` library determines the local time zone based on the coordinates.

4. **Weather Data**: The app makes an API call to OpenWeatherMap to fetch current weather data for the city.

5. **Display**: The retrieved information is displayed in a user-friendly format, including:
- Current local time
- Temperature in Celsius
- Weather condition
- "Feels like" temperature
- Wind speed
- Humidity percentage
- Weather description
- Atmospheric pressure

## Error Handling

If an invalid city name is entered or any other error occurs during the process, an error message is displayed to the user.

## GUI Components

- Search box with an icon
- Weather logo
- Display areas for various weather parameters
- Stylish bottom box for presenting weather details

## Customization

You can easily customize the app's appearance by modifying the GUI components and replacing the image files with your own designs.

## Note

This app requires an active internet connection to fetch real-time weather data and geolocation information.

## License

[Include your license information here]

## Acknowledgments

- OpenWeatherMap for providing the weather data API
- Icons and images used in this project [Include credits or sources for your images]

Feel free to contribute to this project by submitting pull requests or reporting issues!

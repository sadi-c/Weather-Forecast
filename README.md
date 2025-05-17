🌦️ Weather CLI Tool

A simple Python command-line application that fetches and displays real-time weather data for any city using the OpenWeatherMap API.

📌 Features

Retrieves current temperature, humidity, pressure, and weather description
Uses OpenWeatherMap REST API
Parses and displays data in a user-friendly format
Basic error handling for invalid city names
🚀 Getting Started

Prerequisites
Python 3.x
requests library
Install via pip if not already installed:
pip install requests
Installation
Clone the repository:
git clone https://github.com/yourusername/weather-cli.git
cd weather-cli
Get a free API key from OpenWeatherMap.
Set your API key as an environment variable:
Linux/macOS:

export API_KEY=your_api_key_here
Windows (CMD):

set API_KEY=your_api_key_here
Windows (PowerShell):

$env:API_KEY="your_api_key_here"
Run the script:
python weather.py
📷 Example Output

Enter city name : New York
Temperature (in kelvin unit) = 293.15
Atmospheric pressure (in hPa unit) = 1013
Humidity (in percentage) = 56
Description = clear sky
⚠️ Notes

API returns temperature in Kelvin by default. You can modify the script to convert it to Celsius or Fahrenheit if desired.
Error handling is included for invalid city names.
🛠️ Possible Improvements

Convert temperature units to Celsius/Fahrenheit
Add support for forecasts
Write unit tests for API handling
Create a GUI or web version using Flask

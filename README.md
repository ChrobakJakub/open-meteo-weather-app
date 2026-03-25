# Open-Meteo Weather App

A simple Python application that uses the Open-Meteo API to download weather data and generate:

- console output,
- a CSV file,
- a TXT summary,
- a PNG temperature chart.


## How it works

1. The application sends an HTTP GET request to the Open-Meteo API.
2. The API returns weather data in JSON format.
3. The script extracts current weather data and a 7-day forecast.
4. The data is processed in Python using pandas.
5. The application saves the forecast to a CSV file and a text summary.
6. It also generates a PNG chart showing minimum and maximum temperatures
   

## API used

**Open-Meteo API**  
Website: https://open-meteo.com/

## Features

- Downloads current weather data
- Downloads 7-day forecast data
- Saves daily forecast to `forecast.csv`
- Saves weather summary to `summary.txt`
- Generates a temperature chart in `temperature_chart.png`

## Project structure

```text
open-meteo-weather-app/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── output/
    └── .gitkeep

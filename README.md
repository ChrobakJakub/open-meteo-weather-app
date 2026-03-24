# Open-Meteo Weather App

A simple Python application that uses the Open-Meteo API to download weather data and generate:

- console output,
- a CSV file,
- a TXT summary,
- a PNG temperature chart.

## Project goal

This project was created as a small programming/scripting assignment.  
The application connects to a public API, processes the returned JSON data, and generates useful output files.

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

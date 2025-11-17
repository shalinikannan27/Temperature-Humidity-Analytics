# Temperature & Humidity Analytics Dashboard

This project simulates IoT sensor devices generating temperature and humidity data, analyzes the data, and presents it in an interactive dashboard. The goal is to demonstrate **end-to-end IoT analytics in a networked environment**, including data collection, storage, analysis, and visualization.

## Live Demo

You can access the live dashboard here:  
[Temperature & Humidity Analytics Dashboard](https://temperature-humidity-analytics.lovable.app/)

## Features

- **Simulated Sensor Devices:** Generates fake temperature and humidity data for multiple devices.
- **Data Storage:** Saves sensor readings into a CSV file for analysis.
- **Analytics:**
  - Average temperature across all devices
  - Highest humidity recorded
  - Detection of abnormal values (temperature > 35°C, humidity < 40% or > 70%)
- **Interactive Dashboard:**
  - View raw sensor data
  - View analytics results in tables
  - Visualize temperature and humidity trends per device
  - Highlight abnormal values in charts

## Technology Stack

- **Python**
- **Pandas** – for data manipulation and analytics
- **Matplotlib** – for plotting charts
- **Streamlit** – for creating the interactive dashboard



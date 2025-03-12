# Bike Sharing Analytics
### This repository contains the notebook and datasets used to conduct detailed analytics on BayWheels ridesharing data. It is merged with Weather Data which was extracted from https://www.weatherforyou.com/ for the San Franciso Region over a period of 6 years starting from 1st January 2018 to 28th Feb 2025. It doesn't get fresher than this!

---

# Bay Area Bike Share Analysis

This project is an end-to-end data science portfolio that analyzes bike sharing in the San Francisco Bay Area. The goal is to explore and understand the factors influencing bike usage patterns, rider behavior, and route popularity by combining multiple datasets:

- **Bike Share Data:** Detailed trip-level information including start/end times, stations, durations, and user types.
- **Weather Data:** Hourly weather conditions (temperature, humidity, wind, etc.) to study their impact on bike usage.
- **Station Data:** Metadata on bike share stations (location, dock count, kiosk availability, and neighborhood information) to support spatial analysis.

## Project Overview

The analysis involves several key steps:

1. **Data Integration:**  
   The bike share, weather, and station datasets are merged to form a comprehensive dataset. This allows us to link trip details with weather conditions and station attributes.

2. **Exploratory Data Analysis (EDA):**  
   We conduct EDA to investigate trends such as:
   - Distribution of trip durations and distances.
   - Temporal patterns in bike usage (hourly, daily, and monthly trends).
   - Differences in usage between subscriber and casual users.
   - Spatial patterns and popular routes visualized through interactive maps.

3. **Feature Engineering:**  
   Additional features are derived from the raw data, including:
   - Converting time columns to appropriate datetime formats.
   - Extracting wind direction and converting wind speeds from MPH to KM/H.
   - Imputing missing station attributes using a nearest neighbor approach based on geolocation.

4. **Visualization and Insights:**  
   Various visualizations such as histograms, bar plots, correlation heatmaps, pairplots, and interactive maps are generated to reveal:
   - How weather affects bike usage.
   - Hourly and monthly trends in trips.
   - Popular routes and potential areas for station expansion.

## Outcome

The insights drawn from this project can help:
- Understand the influence of weather and time on bike share usage.
- Identify popular routes and areas with high demand.
- Inform operational strategies for optimizing station locations and managing the bike share fleet.

This project is continuously evolving, and additional analyses (such as predictive modeling for trip demand) are planned for future iterations.

---

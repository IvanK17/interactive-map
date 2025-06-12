# Interactive Crop Monitoring Map

This interactive map is designed to help Meijer Potato monitor crop performance in their trial fields using drone-captured data. The tool allows users to explore key indicators such as vegetation height and coverage, filtered by location, variety, and date.

## Project Overview

The map provides a visual overview of crop growth across different field plots. Users can filter the data by selecting specific locations, potato varieties, and dates. Each plot on the map can be clicked to reveal detailed information, including:
- Field number
- Variety name
- Vegetation height (p75)
- Vegetation cover (%)
- Flight date
- Location

Crop growth stages are visually represented through icons to make interpretation quicker and more intuitive.

In addition to the data visualization features, the latest version includes a prediction model that estimates drone-based vegetation measurements using weather data and lag features.

## Features

- Interactive field map with clickable plots
- Filters for date, location, and variety
- Plot-level crop data and growth stage visualization
- Predictive model based on historical weather conditions
- Responsive and accessible user interface
- Hosted online via GitHub Pages

## Technologies Used

- Python (for data preparation and generating the HTML structure)
- JavaScript and Leaflet (for interactive map rendering)
- HTML/CSS (for layout and styling)
- Flatpickr (for calendar selection)
- GitHub Pages (for hosting the map)

## How to Access

The map is accessible at the following link:  
👉 [https://ivank17.github.io/interactive-map/](https://ivank17.github.io/interactive-map/)

## Documentation

A separate ZIP folder is included in the project submission. It contains step-by-step documentation explaining how to use the map, interpret the displayed data, and navigate the available features.

## Development Notes

This tool was developed as part of the data science minor 2025 in collaboration with Meijer Potato.

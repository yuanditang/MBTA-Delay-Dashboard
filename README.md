# MBTA Delay Analysis Dashboard 🚇📊

This interactive web-based dashboard provides a visual and analytical overview of delay trends across the MBTA (Massachusetts Bay Transportation Authority) subway system. It enables users to explore delays by year, line, and station using charts, maps, and summary statistics.

## 🚀 Features

- 🗂 **Filterable Dashboard**: View delay data by year, subway line, and station.
- 📊 **Visualizations**:
  - Bar charts for total delays by line and top stations
  - Pie chart for delay distribution
  - Stacked trend chart over the years
- 🗺 **Interactive Map**:
  - Circle size indicates delay hours
  - Color-coded by MBTA line
  - Click to zoom into station locations
- 📋 **Data Table**:
  - Sortable columns
  - Delay shown in both minutes and hours
- 📈 **Summary Stats**:
  - Total delays
  - Most affected line and station
  - Max and average delay metrics

## 🧰 Tech Stack

- **HTML, CSS, JavaScript**
- **D3.js v7** – for data visualization
- **Mapbox GL JS** – for interactive mapping
- **TopoJSON & d3-geo** – for geographical data processing

## 📁 File Structure

├── index.html             # Main dashboard (HTML, JS, and CSS embedded)
├── grouped_delay.csv      # Delay data grouped by year, station, and line
├── station_location.csv   # Geographic coordinates of MBTA stations
└── README.md              # Project documentation


## 📊 Data Notes

- Delays are shown in hours for clarity (minutes / 60).
- Charts and tooltips are interactive and data-driven.
- Table rows are highlighted based on severity.

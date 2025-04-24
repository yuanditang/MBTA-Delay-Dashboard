# 🚇 MBTA Delay Analysis Dashboard

An interactive data visualization dashboard that analyzes subway delay data from the **Massachusetts Bay Transportation Authority (MBTA)** system. This project helps users explore when, where, and how delays happen across subway lines and stations using filters, charts, maps, and tables.

> Built with **D3.js**, **Mapbox GL JS**, and vanilla **HTML/CSS/JavaScript**.
> See reports (here)[reports]

---

## 🖼️ Overview

The dashboard allows users to:

- Filter data by **year**, **subway line**, and **station**
- View delay statistics and trends through **interactive visualizations**
- Explore spatial patterns on an **interactive map**
- Analyze top delay stations, most affected lines, and total delay impact


---

## 🔧 Features

### 🎚 Filters
- **Year**, **Line**, and **Station** dropdowns dynamically populate from data
- Filtered views automatically update all visualizations

### 📊 Charts
- **Bar chart** of total delay minutes by line
- **Pie chart** showing percentage distribution of delays
- **Bar chart** of top 10 most delayed stations
- **Stacked area chart** showing delay trends over time

### 🗺️ Interactive Map
- Circles sized by delay hours, color-coded by MBTA line
- Hover to see station info, click to zoom
- Mapbox-based map centered on Boston

### 📋 Data Table
- Displays raw records by station, year, and delay duration
- Sortable columns
- Rows highlighted based on severity (high/medium/low delay)

### 📈 Summary Statistics
- Total delay minutes and hours
- Average delay per station/year
- Max single delay
- Most affected line and station

---

## 🧰 Technologies Used

| Tech         | Purpose                          |
|--------------|----------------------------------|
| HTML & CSS   | Structure and styling            |
| JavaScript   | Interactivity and DOM logic      |
| D3.js v7     | Data visualization               |
| Mapbox GL JS | Interactive map                  |
| TopoJSON     | Map geo-processing (if extended) |
| CSV data     | Used for delays and station info |

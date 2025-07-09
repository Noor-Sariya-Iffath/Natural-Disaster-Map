# Natural Disaster Tracker

A simple, browser-based application that displays real-time natural disaster events on an interactive world map using NASA’s EONET API.

## Features

- Real-time disaster data from NASA
- Interactive map (Leaflet + OpenStreetMap)
- Filter by category (e.g., Wildfires, Storms)
- Customizable date range (1–365 days)
- Responsive design for mobile and desktop

## How to Run

### Method 1: Open Directly
1. Download or clone the project.
2. Open `natural_disaster_tracker.html` in any modern web browser.

### Method 2: Run with Local Server (Recommended for Chrome users)
```bash
cd path/to/project
python3 -m http.server 8000
````

Then open `http://localhost:8000/natural_disaster_tracker.html`.

## Requirements

* A web browser (Chrome, Firefox, Safari, Edge)
* Internet connection (to fetch live data and map tiles)


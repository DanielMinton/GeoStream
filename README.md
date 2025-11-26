# GeoStream

Live flight tracking with real-time ADS-B data visualization on an interactive map.

## Overview

GeoStream is a real-time aircraft tracker powered by the OpenSky Network API. It displays live flight positions on an interactive dark-themed map with altitude-coded colors, detailed flight information panels, and regional filtering.

## Features

- **Interactive Map**: Leaflet.js with CartoDB Dark Matter tiles
- **Real-time Aircraft**: Live positions updated every 30 seconds
- **Altitude Color Coding**: Visual distinction by flight level
- **Detailed Flight Panel**: Click any aircraft for comprehensive data
- **Region Filtering**: Focus on USA, Europe, Asia, or World
- **Flight List**: Sortable list of active aircraft

## Technical Stack

- **Leaflet.js** - Interactive mapping library
- **CartoDB Dark Matter** - Dark-themed map tiles
- **OpenSky Network API** - Real-time ADS-B flight data
- **JavaScript** - Client-side application
- **HTML/CSS** - Single-file static deployment

## Data Displayed

For each aircraft:
- Callsign
- Registration country
- Altitude (feet)
- Ground speed (knots)
- Heading (degrees)
- Vertical rate (ft/min)
- Position (lat/lng)
- ICAO24 transponder code
- Squawk code

## Altitude Color Legend

- Green: Ground - 10,000 ft
- Blue: 10,000 - 25,000 ft
- Purple: 25,000 - 35,000 ft
- Pink: 35,000+ ft

## API Information

Data sourced from OpenSky Network (opensky-network.org), which provides:
- Free tier with rate limits
- ADS-B aircraft position data
- Global coverage
- ~10 requests/minute for anonymous users

## Demo

View the live demo at: https://danielminton.github.io/GeoStream/

## Usage

Simply open index.html in a browser or visit the GitHub Pages demo. Select a region to filter aircraft and click any plane for detailed information.

## Author

Daniel Minton
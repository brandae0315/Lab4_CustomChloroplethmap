# Lab4_CustomChloroplethmap
## Global CO₂ Emissions by Continent (2023)

An interactive **choropleth map** built with **HTML**, **CSS**, and **JavaScript** using the **Leaflet** mapping library.  
The map visualizes **total carbon dioxide (CO₂) emissions (in tons)** per continent for the year **2023**, using data from [Our World in Data](https://ourworldindata.org/grapher/annual-co2-emissions-per-country).

---

## Overview

This project displays a world map where each continent is shaded based on its total CO₂ emissions for 2023.  
Users can **hover** over each continent to view the exact emission values, or **click** to zoom in. 
The color symbology follows a **Purple–Red (PuRd)** sequential palette from [ColorBrewer](https://colorbrewer2.org/), making higher emissions visually stand out in deeper red-purple tones.
Base Map is from [OpenStreetMap Tiles](https://www.openstreetmap.org/) ; Mapping libraries [Leaflet.js](https://leafletjs.com/) 

---

## Features

 **Interactive Leaflet map** centered globally  
 **Choropleth symbology** using a sequential Purple–Red color scale  
 **Hover interaction** that highlights continents and displays CO₂ emission data  
 **Legend** showing emission ranges in tons  
 **Zoom-on-click** functionality    

---

##  Data Source

- **Dataset:** [Annual CO₂ Emissions per Country – Our World in Data](https://ourworldindata.org/grapher/annual-co2-emissions-per-country)  
- **Units:** Metric tons of CO₂  
- **Temporal coverage:** 2023  
- **Processing:** Country-level data was aggregated by continent and exported as a GeoJSON file (`contCO2emis2023.geojson`).

---
Author: Alexandra Brand





# Disaster Risk Dashboard - Frontend

A high-performance, premium GIS dashboard for monitoring disaster impacts on telecommunication infrastructure (OLT nodes) across Thailand.

## Features
- **Longdo Map Integration**: Precise Thai-localized map tiles.
- **Seamless Blur Zones**: Heatmap-like visualization of 13-year historical flood recurrence.
- **Real-time Monitoring**: Visual indicators for "Node Down" status with interactive popups.
- **Dynamic Theme Engine**: Premium Light and Dark mode switcher with persisted settings.
- **Impact Alerts Sidebar**: AI-enriched alert cards showing risk levels, severity, and scheduling.
- **PEA Timing**: Displays scheduled power outage windows (Start - End times).

## Tech Stack
- HTML5 / CSS3 (Vanilla)
- Vanilla JavaScript (ES6+)
- Leaflet.js
- Lucide Icons (Webfonts)

## Setup & Running
1. Deploy the contents of this folder to any static web server (NGINX, Apache, etc.).
2. **Backend Connection**: By default, it looks for the API at `http://localhost:8000`. 
3. Open `index.html` in your browser.

## Configuration
Inside `index.html`, you can adjust:
- `API_BASE_URL`: The URL of your standalone Backend API.
- `longdoKey`: Your personal Longdo Map API key.

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
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Spykurb/disaster-frontend.git
   cd disaster-frontend
   ```
2. **Local Configuration**:
   - Open `index.html` and verify the `API_BASE_URL` matches your running Backend (default is `http://localhost:8000`).
   - Ensure you have a valid **Longdo Map API Key** set in the `longdoKey` variable.
3. **Run the Dashboard**:
   - Deploy the contents to any static web server (NGINX, Apache) or simply use a local python server for testing:
     ```bash
     python3 -m http.server 8080
     ```
   - Open `http://localhost:8080` in your browser.

## Configuration
Inside `index.html`, you can adjust:
- `API_BASE_URL`: The URL of your standalone Backend API.
- `longdoKey`: Your personal Longdo Map API key.

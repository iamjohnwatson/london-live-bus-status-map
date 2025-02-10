# TfL Bus Live Tracker

TfL Bus Live Tracker is a responsive web application that displays real-time bus arrival information at nearby TfL bus stops in London. It uses the TfL API for live data, Leaflet.js for interactive mapping, and the Web Speech API for spoken bus arrival updates.

## Features

- **Real-Time Bus Arrivals:** Displays live bus arrival times at the five nearest bus stops.
- **Interactive Map:** Powered by Leaflet.js, with a toggle between standard map and satellite views.
- **Location Search:** Search by place name or postcode (using Nominatim for geocoding) to recenter the map.
- **Geolocation:** Option to use your device’s location to find nearby bus stops.
- **Drop a Pin:** Click anywhere on the map to select a new location.
- **Speech Synthesis:** Announces the nearest bus stop and upcoming buses using a British accent.
- **Beep Feedback:** Provides auditory feedback (using a local `beep.wav` file) when the location is updated.
- **Responsive Design:** Optimized for both desktop and mobile browsers.

## Technologies Used

- **HTML, CSS, JavaScript** – Core web technologies.
- **Leaflet.js** – For interactive maps.
- **TfL API** – For real-time bus stop and bus arrival data.
- **Nominatim (OpenStreetMap)** – For geocoding place names.
- **Web Speech API** – For text-to-speech functionality.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/tfl-bus-live-tracker.git
   cd tfl-bus-live-tracker

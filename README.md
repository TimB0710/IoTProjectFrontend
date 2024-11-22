# Real-Time Dashboard with Chart.js

This project is a **real-time dashboard** that visualizes **live data** (via WebSocket) and **historical data** (via
REST API) using **Chart.js**.

## Features

- **Live Data**: Dynamically updates charts as data is received over WebSocket.
- **Historical Data**: Fetches and displays past data based on a selected date.
- **Dark Mode**: Toggle between light and dark themes for better visibility.
- **Responsive Design**: The dashboard adapts to different screen sizes for an optimized experience on mobile and
  desktop.

## Data Structure (needs refactoring..)

### Live Data

```json
{
  "topic": "sensor_id",
  "value": 42.5
}
```

### Historical Data

```json
[
  {
    "topic": "sensor_id",
    "timestamps": [
      "10:00",
      "10:01",
      "10:02"
    ],
    "values": [
      42.1,
      42.3,
      42.5
    ]
  }
]
```

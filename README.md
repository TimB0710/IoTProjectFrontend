# Real-Time Dashboard with Chart.js

This project is a simple real-time dashboard that visualizes **live data** (via WebSocket) and **historical data** (via REST API) using Chart.js.

## Features
- **Live Data**: Dynamically updates charts as data is received over WebSocket.
- **Historical Data**: Fetches and displays past data based on a selected date.

## Data Structure

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
        "timestamps": ["10:00", "10:01", "10:02"],
        "values": [42.1, 42.3, 42.5]
    }
]
```
## Setup
* Replace wss://toBeDone with your WebSocket server URL.
* Replace https://toBeDone with your REST API URL.
* Open the HTML file in a browser.
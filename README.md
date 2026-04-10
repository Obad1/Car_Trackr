Fleet Tracker CLI

A lightweight Python application designed to simulate a vehicle tracking system. This tool allows users to initialize a fleet of vehicles, assign random attributes, and simulate movement within a specific geographic bounding box.

## 🚀 Features

  * **Dynamic Fleet Generation:** Supports tracking between 2 and 4 vehicles simultaneously.
  * **Randomized Attributes:** Automatically assigns car colors, luxury brands (Toyota, Benz, Bugatti, etc.), and unique registration numbers.
  * **Coordinate Simulation:** Simulates movement within specific latitude/longitude ranges (default set to the Lagos, Nigeria region).
  * **Interactive Menu:** Simple CLI interface to drive vehicles, view current locations, or terminate the system.

## 🛠️ Requirements

  * Python 3.x

## 📂 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Obad1/fleet-tracker-cli.git
    cd fleet-tracker-cli
    ```
2.  **Execute the script:**
    ```bash
    python fleet_tracker.py
    ```

 Logic Overview

  * **`TrackingFleet` Class:** Encapsulates the fleet data and coordinate boundaries.
  * **`defineCar`:** Initializes the fleet list with randomized data.
  * **`driveCar`:** Updates the latitude and longitude of every vehicle in the fleet to simulate a new destination.
  * **`trackCar`:** Formats and prints the current status and GPS coordinates of all active vehicles.

## 📝 Example Output

```text
Car 1: Silver Benz REG5823
Location: 6.5142°N, 3.3891°E

Car 2: Orange Bugatti REG1294
Location: 6.5187°N, 3.3912°E
```

## 📜 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

# FALL DETECTION SYSTEM

## Overview
This project is a **prototype of a wearable fall detection system** designed to monitor and detect sudden falls in real-time, especially for elderly individuals or patients. 
It uses sensors (like an accelerometer and gyroscope) to track body movement, calculates acceleration magnitude, and determines if a fall has occurred based on threshold values. When a fall is detected, the system:
- Records the event along with time, date, and sensor data.
- Sends alerts (e.g., SMS notifications).
- Stores the data in a `data.ini` file.
- Displays the event through a web-based dashboard built with PHP.

---

## Key Components

- **ESP32 Microcontroller**:  
  Processes sensor data and controls communication.

- **Gyroscope Sensor**:  
  Monitors balance and detects sudden movements (falls).

- **GPS Module**:  
  Retrieves real-time location information.

- **GSM SIM Module**:  
  Sends SMS alerts when a fall is detected.

- **Embedded C**:  
  Programming language used for firmware development.

- **Web Application**:  
  Built using PHP, JavaScript, and an INI file system. It displays:
  - Movement data  
  - Time and date  
  - Fall detection events for monitoring

---

## Files Used
- `app.php`: Main dashboard interface
- `data.ini`: Stores sensor and fall data
- `getVariables.php`: Reads data for display
- `setVariables.php`: Updates data.ini with new values
- `css/style.php`: Styles for the web interface
- `js/jquery.min.js`: JavaScript for dynamic updates

---

## Purpose
The system aims to enhance **personal safety and rapid emergency response** by detecting falls promptly and notifying caregivers or emergency contacts.



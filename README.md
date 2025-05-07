<html>
<title><h2>FALL DETECTION</h2></title>
<body>
<p>
  The prototype of wearable fall detection system designed to monitor and detect sudden falls in real-time, especially for elderly individuals or patients. It uses sensors (like an accelerometer and gyroscope) to track body movement, calculates acceleration magnitude, and determines if a fall has occurred based on threshold values. When a fall is detected, the system records the event along with time, date, and sensor data, and can trigger alerts (e.g., SMS). This data is stored in a file (data.ini) and displayed through a web-based dashboard built with PHP</p>
<p><h3>Key Components:</h3>
      *ESP32 Microcontroller: Processes sensor data and controls communication.
      *Gyroscope Sensor: Monitors balance and detects sudden movements (fall).
      *GPS Module: Retrieves real-time location.
      *GSM SIM Module: Sends SMS alerts when a fall is detected.
      *Embedded C: Programming language used for firmware development.
      *Web Application (PHP, JS, INI file): Displays movement data, time, date, and fall events for monitoring.

    </p>
  </body>
</html>

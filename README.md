# Power-Quality-Analysis
An open-source IoT Power Quality Analyzer designed for continuous monitoring of AC electrical lines using the ESP32. This project provides a cost-effective solution for diagnosing power issues like harmonic distortion and voltage instability.
Core Functionality:

* Measures Voltage, Current, and Frequency
* Computes Voltage and Current THD (Total Harmonic Distortion) via FFT
* Detects and flags voltage transients (sags/swells)
* Reports data via MQTT for cloud integration and automated alerts
* Includes a local OLED display for immediate readings

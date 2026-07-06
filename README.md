#IoT Health Monitor — Smart Battery & Machine Health Monitoring Platform

IoT Health Monitor is an end-to-end embedded and IoT monitoring platform for battery and machine health monitoring.

The project uses an ESP32 sensor node to collect system data such as temperature, voltage, current, power, vibration, uptime, Wi-Fi signal strength, and device status. The data will later be sent to a Python backend, stored in a database, and displayed on a live dashboard with alerts, health scoring, and predictive maintenance logic.

## Project Objectives

* Build a professional ESP32-based IoT monitoring device.
* Measure battery and machine health parameters.
* Detect warning and critical fault conditions.
* Send sensor readings wirelessly to a backend system.
* Store readings and alerts in a database.
* Display live system status, graphs, alerts, and health scores on a dashboard.
* Document the project clearly for engineering portfolio and CV use.

## Planned System Layers

1. ESP32 embedded device
2. Sensor system
3. IoT communication
4. Backend and database
5. Dashboard, analytics, and reports

## Planned Hardware

* ESP32 development board
* INA219 or INA226 voltage/current sensor
* DS18B20 temperature sensor
* MPU6050 vibration/motion sensor
* OLED I2C display
* Buzzer
* RGB LED or status LEDs
* Relay module
* Push button
* Breadboard and jumper wires

## Planned Software Stack

### Embedded

* ESP32
* Arduino C/C++
* Wi-Fi communication
* Sensor integration
* Local alert logic

### Backend

* Python
* FastAPI
* SQLite
* Pydantic
* Uvicorn

### Dashboard

* Streamlit
* Pandas
* Plotly
* Requests

## Week 1 Progress

* [x] Project name selected
* [x] GitHub repository created
* [x] Professional folder structure created
* [x] ESP32 blink test completed
* [ ] First firmware file uploaded
* [ ] First GitHub commit completed

## Current Status

Project setup in progress.

## Final Goal

By the end of this project, IoT health monitor should demonstrate embedded systems, IoT communication, backend development, database storage, dashboard analytics, alert handling, and engineering documentation.


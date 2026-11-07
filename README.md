# IoT-Based Water Tank Level and Quality Measurement System

An automated Industrial IoT (IIoT) prototype designed to monitor water tank levels and key quality parameters in real time using an ESP32 microcontroller.

## 🚀 Features
- **Real-time Level Monitoring:** Tracks fluid height to prevent tank overflows and pump dry-running.
- **Water Quality Metrics:** Measures pH, Total Dissolved Solids (TDS), and turbidity.
- **Cloud Dashboard:** Transmits data via Wi-Fi to a remote dashboard for live visualization.

## 🛠️ Hardware Components
- ESP32 Microcontroller
- Ultrasonic/Level Sensor
- pH Sensor, TDS Sensor, and Turbidity Sensor
- Jumper wires, breadboard, and power supply

## 📂 Project Structure
- `/src` - Contains the Arduino/C++ source code.
- `/schematics` - Circuit wiring diagrams.
- `/images` - Photos of the physical setup and dashboard.

## 📊 How It Works
1. Sensors collect physical and chemical data from the water tank.
2. The ESP32 processes the signals and connects to Wi-Fi.
3. Data is pushed to the cloud dashboard for remote monitoring and alerts.

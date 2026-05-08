# GRID-EYE: Smart Power Distribution Monitoring System

GRID-EYE is a multi-node embedded system designed to monitor, analyze, and secure power distribution networks using real-time sensing and IoT-based visualization.

## 🚀 Overview
Traditional power systems lack real-time visibility at distribution nodes, leading to energy theft, overloads, and inefficiencies. GRID-EYE addresses this by implementing a smart monitoring architecture capable of detecting anomalies and visualizing power flow across multiple nodes.

## 🧠 Key Features
- Multi-node current monitoring using ACS712 sensors
- Real-time data acquisition via ESP32
- Overload and abnormal consumption detection
- Temperature monitoring for fault detection
- Energy theft detection using mismatch analysis
- IoT dashboard visualization using Blynk
- Gmail-based alert system for anomaly notifications

## ⚙️ Tech Stack
- ESP32 Microcontroller
- ACS712 Current Sensors
- Temperature Sensors
- Embedded Systems
- Blynk IoT Cloud
- Gmail Notification Integration
- Real-time Data Logging

## 🔄 System Architecture
1. Power is distributed across multiple nodes (H1, H2, H3)
2. Each node is monitored using current sensors
3. ESP32 processes incoming data continuously
4. Data is analyzed for anomalies:
   - Overload conditions
   - Power theft (input-output mismatch)
   - Temperature rise
5. Processed data is sent to the Blynk dashboard
6. Alerts are triggered via email when anomalies are detected

## 📊 Dashboard & Alerts
- Real-time energy monitoring using Blynk dashboards
- Graphical visualization of node-wise consumption
- Instant Gmail alerts for theft or overload events

## 🌍 Applications
- Smart grid monitoring systems
- Industrial power distribution analysis
- Energy theft detection systems
- Real-time electrical infrastructure monitoring

## ⚙️ System Overview
The system uses multiple ACS712 current sensors to monitor power flow across different distribution nodes. An ESP32 microcontroller collects and analyzes real-time data to detect overloads, power theft, and abnormal consumption patterns. Data is visualized through the Blynk IoT dashboard, while alerts are triggered via email for anomaly detection.

## 📌 Status
Prototype developed with real-time monitoring, dashboard visualization, and alert system integration. Further optimization and scaling planned.

## 📸 Project Demonstration

### 🔹 Blynk Dashboard (Real-time Monitoring)
Displays node-wise energy consumption and total energy usage in real time.

### 🔹 Gmail Alert System
Triggers instant alerts when abnormal conditions such as power theft are detected.

### 🔹 Hardware Prototype
Physical implementation of the multi-node monitoring system with sensors, transformer, and ESP32 integration.

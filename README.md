# AI-Enabled Mine Subsidence Monitoring & Early Warning System

**SIH 2026 | Problem Statement: SIH26025**

## About the Project

An AI-powered, low-cost monitoring system designed to detect abnormal ground behaviour and support early identification of potential land subsidence in underground coal mining regions.

The proposed solution combines distributed IoT sensor networks, machine learning, mathematical modelling, and real-time data visualization to improve mining safety.

## Key Features & Innovations

- **Distributed Sensor Network:** Multiple sensor nodes monitor vibration, tilt, displacement and other ground-related parameters.
- **XGBoost:** Performs supervised classification of sensor patterns for risk assessment.
- **Isolation Forest:** Identifies unusual sensor behaviour through unsupervised anomaly detection.
- **Thermal Compensation Model:** Uses the mathematical equation ΔL = α × L₀ × ΔT to estimate temperature-induced expansion and distinguish it from actual ground displacement.
- **Thermal-Protected Enclosure:** Proposed protective housing to safeguard sensor electronics in harsh environments.
- **Spatial Anomaly Analysis:** Compares neighbouring sensor readings to identify localized abnormalities.
- **LoRa Communication:** Proposed wireless multi-hop communication between distributed nodes.
- **Live Monitoring Dashboard:** Firebase-connected interface for sensor data visualization.

## Technology Stack

ESP32 | IoT Sensors | LoRa | Python | XGBoost | Isolation Forest | Firebase | Web Technologies

## Current Implementation

- Seven-node prototype using synthetic sensor data.
- Firebase integration for data storage.
- XGBoost and Isolation Forest implementation.
- Online-connected monitoring dashboard.

## Future Scope

- Physical sensor deployment in mining environments.
- Integration of real-world geological datasets.
- Edge AI processing using NVIDIA Jetson Nano.
- GIS-based subsidence visualization.
- Field validation and improved early-warning mechanisms.

## Project Status

Currently a prototype, not yet field-deployed or validated using real mine measurements.

**Our Vision:** Making underground mining safer through affordable IoT technology, intelligent anomaly detection, and data-driven geological monitoring.

**Developed for Smart India Hackathon 2026 – SIH26025.**

Lunar Mission Digital Twin

An interactive, browser-based digital twin of the Artemis II mission that enables real-time monitoring, anomaly detection, and failure scenario simulation.

Overview

This project simulates a space mission environment by replicating key mission parameters such as fuel, velocity, temperature, and signal strength.

It provides:

Real-time telemetry visualization
Anomaly detection and alerts
Failure scenario simulation
Trajectory visualization
Security and data integrity features

The goal is to demonstrate how digital twins can support decision-making in mission-critical systems.

Problem Statement

Modern space missions lack accessible tools for:

Real-time monitoring
Predictive anomaly detection
Safe simulation of failure scenarios

This makes it difficult to anticipate risks and make informed decisions.

Solution
This project introduces a web-based digital twin that:

Simulates mission stages interactively
Detects anomalies in telemetry data
Allows users to test failure scenarios
Provides actionable insights

Key Features

Real-Time Dashboard
Displays mission metrics:
Distance
Velocity
Fuel
Temperature
Signal strength

Telemetry Visualization
Dynamic charts using Chart.js
Tracks trends across mission stages

Anomaly Detection Engine
Rule-based detection system
Flags:
Low fuel
High temperature
Velocity deviations
Suggests corrective actions

What-If Simulation Lab
Simulate failure scenarios:
Fuel depletion
Signal loss
Thermal overload
Trajectory deviation
View impact + recommended fixes

Trajectory Visualization
Canvas-based rendering of:
Earth → Moon → Return path
Real-time spacecraft position

Security Layer
SHA-256 hashing of telemetry data
Audit logs for system events
Simulated encryption indicators


Tech Stack
Frontend
HTML5
CSS3
JavaScript (Vanilla)
Visualization
Chart.js
Canvas API
Logic & Simulation
JavaScript-based simulation engine
Event-driven updates
Security
Web Crypto API (SHA-256 hashing)

How It Works
User selects mission stage via slider
System updates telemetry data
Anomaly engine evaluates parameters
Charts and visuals update in real time
Alerts and recommendations are displayed
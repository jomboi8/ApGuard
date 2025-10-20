### ApGuard — AI-Powered Intrusion Detection & Prevention for Wi-Fi Networks

A next-generation intelligent security tool for monitoring and protecting wireless networks against modern cyber threats.

ApGuard is an AI-driven Intrusion Detection and Prevention System (IDPS) that combines traditional rule-based analysis with machine learning to detect and respond to cyberattacks in Wi-Fi networks.
It focuses on tackling vulnerabilities common in public and enterprise hotspots  such as Denial-of-Service (DoS/DDoS), Man-in-the-Middle (MITM) and Evil Twin attacks using a hybrid detection model for real-time network defense.

### Problem Overview

Modern Wi-Fi networks face increasingly complex cyberattacks that exploit weaknesses in unmonitored or lightly secured infrastructures.
Existing detection tools are often:

Expensive or complex for small networks to deploy

Static, relying solely on signature-based methods

Unable to adapt to new and evolving attack patterns

ApGuard addresses these challenges by integrating machine learning–driven anomaly detection with real-time packet analysis, enabling dynamic identification and response to threats.

### Core Features

AI-Powered Threat Detection — Learns normal traffic behavior and flags anomalies in real time.

Hybrid Analysis Engine — Combines rule-based and machine learning approaches for enhanced accuracy.

Real-Time Monitoring — Captures, inspects, and visualizes live network packets using Scapy and Dash.

Automated Intrusion Response — Executes mitigation actions upon detecting suspicious activity.

Comprehensive Logging — Records detected threats, timestamps, and affected IPs for later analysis.

Extensible Design — Modular architecture allows easy integration with existing network systems.


### System Architecture
┌───────────▼───────────────┐
│  Network Interface        │
└───────────┬───────────────┘
            │ Packet Capture
┌───────────▼───────────────┐
│  Traffic Analyzer (Scapy) │
└───────────┬───────────────┘
            │ Feature Extraction
┌───────────▼───────────────┐
│   AI/Rule Hybrid Engine   │
└───────────┬───────────────┘
            │ Detection
┌───────────▼───────────────┐
│  Response & Logging Layer │
└───────────┬───────────────┘
            │ Visualization
┌───────────▼───────────────┐
│   Dashboard / API Layer   │
└───────────────────────────┘

### Objectives

Design and implement an AI-powered intrusion detection and prevention tool for Wi-Fi networks.

Evaluate performance through controlled ethical simulations (DoS, MITM, Evil Twin).

Demonstrate adaptability of hybrid AI-rule systems for real-time anomaly detection.


### Get started with Installation
```
    git clone https://github.com/jomboi8/ApGuard.git
```

# Vigilant AI-Powered Fall Detection with Embedded LiDAR Technology

An AI-powered healthcare monitoring system that detects human falls using LiDAR and Computer Vision while preserving user privacy through selective camera activation.

## Overview

Traditional fall detection systems depend on wearable devices or continuous camera surveillance, both of which introduce challenges related to comfort, compliance, and privacy.

This project presents an intelligent fall detection system that combines:

- LiDAR-based motion sensing
- AI-powered pose estimation
- Computer Vision
- Edge Computing
- Secure real-time notifications

The system continuously monitors patient movement using LiDAR. The camera activates only after a potential fall has been detected, reducing unnecessary surveillance while enabling visual confirmation.


## Problem Statement

Current fall detection systems often suffer from:

- False alarms
- Wearable device dependency
- Privacy concerns
- User discomfort
- Continuous monitoring

This project addresses these challenges using LiDAR-driven fall detection and selective camera activation.



## Features

- Wearable-free monitoring
- LiDAR-based fall detection
- Privacy-preserving camera activation
- AI-powered pose estimation
- Real-time notifications
- Edge AI processing
- Secure alert transmission
- Hospital-ready architecture


## System Architecture

```
Patient
    │
    ▼
RPLIDAR A1
    │
    ▼
Jetson Nano
    │
    ▼
AI Fall Detection
(OpenPose + YOLO)
    │
    ▼
Fall Detected?
      │
 ┌────┴────┐
 │         │
No        Yes
 │         │
 │    Activate Camera
 │         │
 │         ▼
 │   Capture Image
 │         ▼
 │ SMTP Notification
 │         ▼
 │ Mobile App Alert
 │
 ▼
Check Again

```

---

## Technology Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| Computer Vision | OpenCV |
| Pose Detection | OpenPose |
| Object Detection | YOLO |
| Machine Learning | CNN |
| Edge AI | NVIDIA Jetson Nano |
| Sensor | RPLIDAR A1 |
| Communication | SMTP |
| SDK | RPLIDAR SDK |
| OS | NVIDIA JetPack |


## Hardware Used

- NVIDIA Jetson Nano
- RPLIDAR A1
- USB Camera
- Edge Computing Device


## Workflow

1. LiDAR continuously scans the environment.
2. Jetson Nano receives depth information.
3. AI models analyze posture.
4. Potential fall detected.
5. Camera activates.
6. Image captured.
7. Alert generated.
8. Notification sent to caregiver.


## Privacy

Unlike conventional surveillance systems, this solution activates the camera only after a suspected fall is detected.

This significantly improves user privacy while maintaining safety.


## Applications

- Hospitals
- Elderly Care
- Rehabilitation Centers
- Smart Homes
- Industrial Safety
- Assisted Living


## Future Improvements

- Mobile application integration
- Cloud dashboard
- Multi-patient monitoring
- Wearable integration
- Edge optimization using TensorRT


## Project Status

Research Prototype


## Authors

- Tharani R.
- Sreevarshan J.
- Sri Siva Kavya R.
- V. Haritha


## Disclaimer

This repository showcases the project architecture, research methodology, and implementation approach developed as part of an academic research project.

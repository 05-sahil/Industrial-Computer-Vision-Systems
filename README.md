# Industrial Computer Vision Systems

This repository contains 3 production-style industrial computer vision systems built using YOLO, OpenCV, and PyTorch. The projects focus on real-time perception, tracking, detection, and safety intelligence for autonomous systems, crowd monitoring, and industrial hazard detection.

--------------------------------------------------

## Dev/Creator

**Sahil Dalal**
GitHub: [@05-sahil](https://github.com/05-sahil)

--------------------------------------------------

## 1. ADAS Perception Pipeline (Autonomous Driving System)

Industrial autonomous driving perception system inspired by real-world ADAS and self-driving stacks.

- Vehicle and pedestrian detection
- Lane detection and road understanding
- Depth estimation
- Multi-object tracking
- Collision risk analysis
- Bird's-eye-view visualization

Use case: Autonomous driving research and simulation systems

--------------------------------------------------

## 2. Smart Crowd Panic Detection System

Industrial safety and surveillance system for real-time crowd monitoring and anomaly detection.

- Human detection and tracking
- Crowd density analysis
- Motion pattern analysis
- Panic and anomaly detection
- Heatmap generation and risk scoring

Use case: Public safety, disaster prevention, and surveillance systems

--------------------------------------------------

## 3. Industrial Fire & Smoke Detection System

Industrial hazard detection system for real-time fire and smoke monitoring in safety-critical environments.

- Fire detection using visual cues and YOLO-based detection
- Smoke detection using motion and color-based analysis
- Hazard level classification (safe, warning, danger)
- Real-time alert system
- Safety zone visualization

Use case: Industrial safety, factories, warehouses, and emergency monitoring systems

--------------------------------------------------

## Tech Stack

- Python 3.11+
- YOLO (Ultralytics)
- OpenCV
- PyTorch
- NumPy
- Supervision

--------------------------------------------------

## Features

- Real-time industrial computer vision pipelines
- GPU acceleration support with CPU fallback
- Multi-object detection and tracking
- Heatmaps and risk visualization
- Cinematic HUD-style overlays
- Production-grade system design

--------------------------------------------------

## Getting Started

Each system is self-contained and automatically installs its own dependencies on first run.

```bash
# Clone the repository
git clone https://github.com/05-sahil/Industrial-Computer-Vision-Systems.git
cd Industrial-Computer-Vision-Systems

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # macOS/Linux

# Run any system (0 = default webcam, or pass a video file path)
cd "Industrial Fire & Smoke Detection System"
python app.py 0
```

--------------------------------------------------

## Goal

To build industrial-grade computer vision systems that replicate real-world AI perception stacks used in autonomous driving, surveillance, and industrial safety monitoring.

--------------------------------------------------

## Note

This repository is intended for educational and research purposes only.
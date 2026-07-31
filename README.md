# Industrial Fire & Smoke Detection System

A real-time industrial hazard detection system for monitoring fire and smoke in safety-critical environments, built using YOLOv8, OpenCV, and PyTorch.

--------------------------------------------------

## Dev/Creator

**Sahil Dalal**
GitHub: [@05-sahil](https://github.com/05-sahil)

--------------------------------------------------

## Overview

This system combines classical computer vision (color/motion analysis) with YOLO-based object detection to identify fire and smoke in a live video feed, classify the hazard level in real time, and display an alert-driven HUD overlay.

- Fire detection using HSV color-space analysis and contour extraction
- Smoke detection using motion analysis (background subtraction + frame differencing) combined with color cues
- YOLOv8-based scene context detection (people/vehicles near the hazard)
- Hazard level classification: CLEAR -> CAUTION -> WARNING -> CRITICAL
- Real-time alert overlay with confidence scoring
- GPU acceleration support with automatic CPU fallback

Use case: Industrial safety, factories, warehouses, and emergency monitoring systems

--------------------------------------------------

## Tech Stack

- Python 3.11+
- YOLO (Ultralytics)
- OpenCV
- PyTorch
- NumPy

--------------------------------------------------

## Getting Started

The script automatically installs its own dependencies on first run.

```bash
# Clone the repository
git clone https://github.com/05-sahil/Industrial-Computer-Vision-Systems.git
cd Industrial-Computer-Vision-Systems

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # macOS/Linux

# Run using webcam (0) or a video file path
cd "Industrial Fire & Smoke Detection System"
python app.py 0
```

Press **Q** to quit the video window.

--------------------------------------------------

## Goal

To build an industrial-grade computer vision system that replicates real-world AI hazard-detection stacks used in industrial safety and surveillance monitoring.

--------------------------------------------------

## Note

This repository is intended for educational and research purposes only.

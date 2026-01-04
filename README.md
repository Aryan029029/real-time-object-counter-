# 🔍 Real-Time Object Counter using YOLOv8

A computer vision project that detects and counts objects in real time using a webcam and the YOLOv8 deep learning model.

<p align="center">
  <img src="screenshots/demo.png" alt="Demo" width="600"/>
</p>

---

## Problem Statement
Manual object counting is inefficient and error-prone.  
This project automates object detection and counting using a real-time video stream.

---

## Features
- Real-time object detection
- Accurate object counting per class
- Webcam-based live inference
- Lightweight YOLOv8 model
- Clean and simple Python implementation

---

## How It Works
1. Captures live video from webcam
2. Applies YOLOv8 object detection
3. Tracks detected objects
4. Displays bounding boxes and count on screen

---

## Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Supervision

---

---
## Installation
1. Install Python 3.8+
2. Install dependencies:
```
pip install opencv-python supervision ultralytics
```

## Usage
Run the script:
```
python object_counter.py
```
- Press 'q' to quit
- Detected objects will be counted and displayed
<img src="demo.png"width="600"/>
## Features
- Real-time object detection
- Object counting per class
- Webcam integration
- Clean visualization with bounding boxes

## License
MIT License

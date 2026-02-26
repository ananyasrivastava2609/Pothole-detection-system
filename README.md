PROJECT UNDER PROGRESS 
 
 
 Real-Time Pothole Detection System Using YOLO and OpenCV
 Overview

This project implements a real-time pothole detection and monitoring system using Computer Vision and Deep Learning. The system detects potholes from dashcam or smartphone video using a pretrained YOLO (You Only Look Once) object detection model, tags the location (GPS – simulated/real), stores detections in a database, and visualizes them on a dashboard.

The goal is to assist municipalities and drivers by providing automated road condition monitoring.

Features
✅ Real-time pothole detection using YOLO
✅ Bounding box visualization with confidence score
✅ GPS coordinate tagging (simulated/real)
✅ Database storage (Firebase / MySQL)
✅ Web dashboard (Flask/Streamlit)
✅ Map visualization of detected potholes
✅ Detection logging with timestamp

Technologies Used
Python
OpenCV
YOLO (Ultralytics / YOLOv5/YOLOv8)
NumPy
Flask / Streamlit
Firebase / MySQL
HTML/CSS (Dashboard)

🏗️ System Architecture
Input video from:
Dashcam
Smartphone camera
Pre-recorded video
Frames extracted using OpenCV
YOLO model performs object detection

Detected potholes:
Bounding box drawn
Confidence score displayed
GPS coordinates tagged
Detection stored in database

Dashboard visualizes:
Location on map
Number of potholes
Detection history

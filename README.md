## Driver Drowsiness and Distraction Detection (YOLOv11)
This is a real-time driver monitoring system designed to detect drowsiness, distraction, and other unsafe behaviors to enhance road safety. Built using YOLOv11, OpenCV, and Pygame, the system processes live webcam input and triggers instant audio alerts upon detecting risky driver behavior.

## Features
Real-Time Monitoring: Continuously captures and analyzes video from the webcam.

Behavior Detection: Identifies critical driver behaviors, including:

Drowsiness

Mobile phone usage

Talking

Head movements (left or right)

Presence of a child in the vehicle

Instant Audio Alerts: Uses pygame to trigger alarms within 0.5 seconds of detection.

Custom YOLOv11 Model: Trained on a tailored dataset of driver behaviors for accurate classification.

Cross-Platform Compatibility: Works on any device with a webcam and Python environment.

## Tech Stack
YOLOv11 – Deep learning model for object detection (Ultralytics framework)

OpenCV – Real-time video and frame processing

Pygame – Audio alert generation

Python 3.8+

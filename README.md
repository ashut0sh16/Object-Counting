# Object-Counting
Real-time object detection and tracking system using YOLOv8 and OpenCV to count unique bottles on an assembly line.

Automated Bottle Counter - YOLOv8

A real-time Computer Vision solution for industrial automation. This project detects and tracks plastic bottles on a conveyor belt, providing an accurate live count using the YOLOv8n (Nano) model.

Features
• Real-time Tracking: Uses `persist=True` to assign unique IDs to each bottle.
• Accuracy: Specifically filtered for COCO class 39 (Bottles) to reduce false positives.
• Performance: Optimized for GPU inference using NVIDIA CUDA.

Tech Stack
• Language: Python 3.12
• AI Model: [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
• Computer Vision: OpenCV
• Data Handling: NumPy


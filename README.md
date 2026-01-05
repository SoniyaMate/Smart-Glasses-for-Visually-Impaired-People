Object-Detection-For-Blind-People-Using-Yolov8-With-Distance-Estimation-of-Multiple-Objects
Smart glasses project for assisting blind people with real-time object detection, distance estimation, and audio feedback.

<img width="1088" height="960" alt="image" src="https://github.com/user-attachments/assets/4e309beb-52e7-4dd2-8eef-aa0e56a29d90" />


Project Aims
Face recognition and object detection system aims to enhance interaction for blind people with their environment using YOLOv8. Core goal focuses on making blind individuals' lives comparable to those without visual impairments through smart glasses technology.
​

Overview
Project employs YOLOv8 for real-time object detection on live camera feeds or video files. Integrates text-to-speech for audio descriptions of detected objects and their estimated distances.
​

Key Features
Real-time object detection using YOLOv8.
<img width="1088" height="960" alt="image" src="https://github.com/user-attachments/assets/c04c912c-f3da-4c8f-bee6-ed36fa82bbd0" />

​

Distance estimation based on object size in frames.
​

Audio feedback via pyttsx3 text-to-speech engine.
​

Support for live video or pre-recorded files.
​

Customizable bounding box colors for detections.
​

Tech Stack
Python 3.x, OpenCV, Ultralytics YOLOv8, NumPy, pyttsx3.
​

Potential integrations: TensorFlow, PyTorch, Google Speech API, GPS via geopy/GPSD.
​

Requirements
Install dependencies with pip:

text
pip install opencv-python pyttsx3 ultralytics numpy
Setup Instructions
Download YOLOv8n.pt model weights and place in weights/ directory.
​

​

Update video_path in main script for video input or use default camera feed.

​

Usage
Run the main script for live detection:

text
python main.py
System detects objects, estimates distances, and announces via speech. Screenshots show bounding boxes with labels and distances on video frames.
​


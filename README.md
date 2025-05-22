# Road_Damage_Detection

This project implements a real-time road damage detection system using the YOLOv8 model for identifying potholes and cracks, along with OpenCV for lane detection. The system captures video input from a webcam or a video file, processes each frame to detect road damages and lane markings, and displays the results in real-time.

Features
Pothole and Crack Detection: Utilizes the YOLOv8 model to identify and highlight potholes and cracks in the road.
Lane Detection: Employs OpenCV techniques to detect lane markings and draw them on the video feed.
Real-Time Processing: Processes video frames in real-time, providing immediate feedback on road conditions.
Requirements
Python 3.x
OpenCV
NumPy
PyTorch
torchvision
ultralytics (for YOLOv8)

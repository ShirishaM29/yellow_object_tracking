Real-time Color Detection using OpenCV
This Python script demonstrates real-time color detection using OpenCV. It captures video from a webcam (or other video source), processes each frame to detect a specific color range in HSV color space, and displays the filtered video stream.

Features:
Color Detection: It detects objects of a specific color range in real-time using HSV color space thresholding.

Video Capture: Utilizes OpenCV's VideoCapture to access frames from the default camera (VideoCapture(0)).

Masking: Creates a binary mask for the detected color range and applies it to the original frame using bitwise operations.

Interactive Display: Displays the original video stream with only the detected color visible.

Requirements:
Python 3.x

OpenCV (pip install opencv-python)

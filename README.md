# Afjal-Khan-25BAI11585-Vityarthi-AiML-project
Lane Detection Project

This project implements a basic Lane Detection System using Python and OpenCV. It detects lane lines on roads from a video file, which is a fundamental concept used in safety-driving cars.

Features:- Detects lane lines in real-time Works with video files Uses edge detection and region masking Simple and beginner-friendly implementation

Project Structure Lane-Detection/

├── lane.py
├── roadbackground short video..mp4
├── README.md

Requirements:-

Make sure you have Python installed (>=3.7)

Install dependencies:-

pip install opencv-python numpy

How to Run:-

Using Video File
Place your video file in the project folder

Update the video path in the code if needed Run:

python lane.py

Replace video capture line with:

cv2.VideoCapture(0)

Run the same command:

python lane.py

Working Principle:-

Convert image to grayscale

Apply Gaussian blur

Detect edges using Canny Edge Detection

Mask region of interest

Detect lines using Hough Transform

Overlay detected lanes on original frame

Common Errors & Fixes:-

Error: No module named cv2

Fix:

pip install opencv-python
Error: Video not opening

Fix: Check file path

Ensure video format is supported (.mp4 recommended)

Contact information:-For any enquires,support or contributions,please contact:afjal.25bai11585@vitbhopal.ac.in

License:-this project is licensed under MIT license,allowing users to freely use, modify and distribute the software with proper attributions

Notes:- This is a basic implementation and may not work perfectly in all conditions performance depends on lighting and road clarity

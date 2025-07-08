# Real-Time Finger Counting using OpenCV

A basic real-time finger counting system built using OpenCV and Python. The project detects a hand in live video feed and counts the number of raised fingers.

## 🔍 Overview

This capstone project uses computer vision techniques to:
- Detect a hand from webcam input
- Identify and count raised fingers
- Display the count live on screen

It's a great introductory project for gesture recognition and real-time image processing using OpenCV.

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy

## 🚀 How It Works

1. Capture live video using OpenCV.
2. Convert the frame to HSV/Grayscale and apply thresholding.
3. Find contours to detect the hand.
4. Use convex hull and defects to count the number of fingers extended.

## 📦 Installation

```bash
git clone https://github.com/your-username/finger-counting-app.git
cd finger-counting-app
pip install -r requirements.txt
python finger_count.py

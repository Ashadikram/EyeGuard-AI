EyeGuard AI 🚗👁️

A real-time Driver Drowsiness Detection System built with OpenCV and Pygame, designed to help drivers stay awake and safe on the road.

⭐ Overview

EyeGuard AI monitors the driver’s eyes using a webcam.
If drowsiness or eye closure is detected, the system instantly plays an alert sound to wake the driver.
It is simple, lightweight, and works on any system with a camera.

🔧 Tech Used

Python

OpenCV – for face & eye detection

Pygame – for playing alert sounds

NumPy

🎯 Features

👁️ Real-time eye monitoring

🚨 Instant sound alert when eyes close

🧠 Smart detection using computer vision

🖥️ Lightweight and fast

✔️ Beginner-friendly code

📸 How It Works

Webcam starts capturing the video feed.

OpenCV detects your eyes using Haar cascades / custom model.

EyeGuard-AI/
│── main.py
│── alert.wav
│── haarcascade_eye.xml
│── haarcascade_frontalface.xml
│── README.md


pip install opencv-python pygame numpy
python main.py


If eyes remain closed for a set duration → ALERT sound plays.

System resets once the driver’s eyes open again.

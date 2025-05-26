🖐️ Hand Gesture Volume Control using OpenCV & MediaPipe
This project allows users to control system volume through simple hand gestures using a webcam. It uses OpenCV for real-time video processing, MediaPipe for accurate hand tracking, and PyAutoGUI to simulate volume key presses based on the distance between the thumb and index finger.

🔧 Features:
Real-time hand tracking using MediaPipe

Dynamic gesture detection (thumb-index finger distance)

Controls system volume (increase/decrease) without touching the keyboard

Works with any standard webcam

🛠️ Technologies Used:
Python

OpenCV

MediaPipe

PyAutoGUI

🎯 How It Works:
The webcam captures live video.

MediaPipe identifies hand landmarks.

The distance between the tip of the thumb (landmark 4) and tip of the index finger (landmark 8) is calculated.

If the fingers are apart beyond a threshold, volume increases. If closer, volume decreases.


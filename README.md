# Hand-Gesture-Volume-Control
A Python project that uses real-time hand tracking via MediaPipe and OpenCV to adjust the system volume based on the distance between your thumb and index finger. Includes a visual volume bar and works on Windows using Pycaw to access system audio.

## Features
- 📷 Real-time webcam hand tracking with MediaPipe
- ✋ Gesture-based control (thumb–index pinch)
- 🔊 Adjusts system volume using Pycaw (Windows)
- 📊 On-screen volume bar visual
- ⌨️ Press spacebar to exit

## Requirements
- Python 3.10
- opencv-python
- mediapipe
- pycaw
- comtypes
- numpy

## How to Run
1. Clone this repository
2. Make sure Python 3.10 is installed
3. Install dependencies:

```bash
pip install opencv-python mediapipe pycaw comtypes numpy

Run the script:
python volume_control.py

 

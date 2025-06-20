# AirBoard- Virtual-Hand-Gesture-Drawing-Board
**AirBoard** is a webcam-based virtual whiteboard that lets you draw in the air using **just your fingers**. It uses Mediapipe for hand tracking and opencv for drawing, color selection, erasing, and board clearing - all through hand gestures.
## Features
- Draw with index finger.
- Erase with two fingers (index and middle finger)
- Clear board with open palm.
- Trackbars to change line color, canvas color, and line thickness.
- Built using Mediapipe for hand tracking and Opencv for real-time rendering.
## How It Works
1. Mediapipe hands detects and tracks 21 hand landmarks.
2. When only the index finger is up -> starts drawing.
3. When only index and middle fingers are up -> erase.
4. When open palm is shown -> clear canvas.
5. Trackbars allow dynamic adjustments of:
    - Drawing color
    - Canvas background color
    - Line thickness
## Requirements
Install the dependies:
'''bash
pip install mediapipe opencv-python

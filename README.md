# HandGestureControl
Volume Control Using Hand Gestures

# Hand Gesture Volume Control

This Python project utilizes computer vision techniques to control system volume through hand gestures. By leveraging OpenCV and MediaPipe libraries, it detects the distance between the thumb and index finger in real-time video streams from a webcam. The detected distance is then mapped to system volume levels, allowing users to adjust the volume by moving their hand closer or farther apart.

## Features

- Real-time hand gesture detection.
- Dynamic volume control based on hand movements.
- Visual feedback on the screen indicating the current volume level.
- Cross-platform compatibility (works on Windows, macOS, and Linux).

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- ctypes
- comtypes
- pycaw

## Installation

1. Clone this repository to your local machine.
2. Install the required Python packages using pip:
   ```
   pip install opencv-python mediapipe comtypes pycaw
   ```
3. Ensure you have a webcam connected to your system.

## Usage

1. Run the `hand_gesture_volume_control.py` script.
2. Position your hand in front of the webcam.
3. Open your thumb and index finger to decrease the volume and close them to increase it.
4. Visual feedback on the screen will indicate the current volume level.
5. Press any key to exit the program.

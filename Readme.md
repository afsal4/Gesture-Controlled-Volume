# Gesture-Controlled-Volume

This application allows you to control the system volume using hand gestures. It utilizes **OpenCV** for video capture and processing and **MediaPipe** for hand tracking. The application is straightforward to use and can be run with a single command.

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/afsal4/Gesture-Controlled-Volume.git
cd Gesture-Controlled-Volume

pip install -r requirements.txt

python volume_control.py
```


## How It Works
- Hand Detection: MediaPipe is used to detect and track your hand in real-time.
Volume Control:
- Pinch Gesture: Use your left hand’s thumb and index finger to make a pinching gesture. This gesture activates the volume control mode.
- Adjust Volume: Once the pinch gesture is detected, move your right hand’s thumb and index finger closer together to decrease the volume, or move them apart to increase the volume.

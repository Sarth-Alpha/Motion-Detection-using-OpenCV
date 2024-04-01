# Motion-Detection-using-OpenCV
This project implements a real-time motion detection system using OpenCV in Python. It captures video frames from a webcam, compares consecutive frames to detect changes indicating motion, and highlights the moving areas with bounding boxes. Detected frames are then saved to an output video file. The system also includes a motion timeout mechanism to stop saving frames if no motion is detected for a specified duration. This project can be used for various applications, such as security surveillance, activity monitoring, and gesture recognition.

## Installation
Make sure you have Python installed on your system.

### Install OpenCV using pip:
     pip install opencv-python

 ## Usage
    1) Run the motion_detection.py script. This will open a window displaying the webcam feed.
    2) The script will detect motion in the feed and highlight it with a bounding box.
    3) Frames with detected motion will be saved to an output video file (output.avi).
## Parameters
    motion_timeout: The duration (in frames) without motion to stop saving.
## Files
    1) motion_detection.py: Python script for motion detection.
    2) output.avi: Output video file containing frames with detected motion.
## Dependencies
    1) Python 3.x 
    2) OpenCV
## License
    This project is licensed under the MIT License - see the LICENSE file for details.

# Motion-Detection-with-MediaPipe-and-OpenCV
This project demonstrates real-time human motion detection using MediaPipe's Pose module and OpenCV. It processes a video to detect and visualize human pose landmarks and displays the frames per second (FPS) for performance evaluation.
## Features
  - Real-time pose detection in a video file
  - Visualizes pose landmarks and connections with customizable styling
  - Displays the FPS on the video feed
  - Adjustable video resolution for better compatibility with different screen sizes.
## Requirements
  - Python 3.8 or higher
  - Required Python Libraries:
      - opencv-python
      - mediapipe
      - time (built-in library)
## How It Works
  - Pose Detection:
      - MediaPipe's Pose model detects 33 human body landmarks in each frame.
      - The landmarks are drawn using mp.solutions.drawing_utils with custom styling.
  -Frame Processing:

      - The video frames are resized to a maximum resolution of 1000x800 pixels to ensure smooth visualization.
  -FPS Calculation:

      - The script calculates and displays the FPS using timestamps to measure performance.
  -Visualization:

      - Landmarks and pose connections are drawn on the frames with green-colored styling for clarity.
## Acknowledgments
  - MediaPipe for the Pose detection solution.
  - OpenCV for video processing.

## Output


# CCTV Motion Detection System

This project uses OpenCV to capture video from a camera and detect motion. It highlights areas with significant motion and provides an alert (sound) when motion is detected. It can be used as a simple CCTV system for security purposes.

## Features

- **Motion Detection**: Detects changes in the video feed to identify motion.
- **Bounding Boxes**: Draws bounding boxes around areas of significant motion.
- **Alert Sound**: Plays a sound alert (using `winsound.Beep`) when motion is detected.
- **Camera Feed**: Displays the live video feed with marked motion areas.

## Requirements

- Python 3.x
- Libraries:
  - `opencv-python` for computer vision tasks (capturing video, detecting motion).
  - `winsound` for playing sound alerts (Windows-specific).

You can install OpenCV using the following command:

```bash
pip install opencv-python

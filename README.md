# OpenCV-Lane-Detection

This project demonstrates lane detection using Python and OpenCV. The system processes road images or video frames to identify lane markings, helping improve autonomous driving and advanced driver assistance systems (ADAS).

---

## Features

- Load and process road images/videos
- Convert frames to grayscale
- Apply Gaussian Blur for noise reduction
- Detect edges using Canny Edge Detection
- Define Region of Interest (ROI)
- Detect lane lines using Hough Transform
- Draw detected lane lines on the original frame
- Real-time lane visualization

---

## Technologies Used

- Python 3.7+
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

---

## Lane Detection Workflow

### Grayscale Conversion
Converts the input image into grayscale for easier image processing.

### Canny Edge Detection
Detects edges by identifying rapid intensity changes.

### Gaussian Blur
Reduces image noise and smooths the image before edge detection.

### Region of Interest (ROI)
Masks unnecessary regions and focuses only on the road lanes.

### Hough Line Transform
Detects straight lane lines from the edge-detected image.

### Lane Overlay
Draws the detected lane boundaries on the original image/video frame.

---

## Algorithm

1. Import required libraries
2. Read input image or video
3. Convert frame to grayscale
4. Apply Gaussian Blur
5. Perform Canny Edge Detection
6. Define Region of Interest (ROI)
7. Apply Hough Line Transform
8. Detect lane lines
9. Draw lanes on the original frame
10. Display final output
---
## Applications

- Autonomous Vehicles
- Advanced Driver Assistance Systems (ADAS)
- Self-Driving Cars
- Traffic Monitoring
- Road Safety Systems
- Computer Vision Research

---

## Result

The implementation successfully detects road lane markings using OpenCV image processing techniques. The combination of edge detection and Hough Transform enables efficient lane tracking for intelligent transportation and autonomous vehicle applications.

---



## License

This project is open-source and available under the MIT License.

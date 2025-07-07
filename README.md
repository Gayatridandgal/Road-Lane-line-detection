# 🚗 Road Lane Line Detection

This project implements a classical computer vision pipeline to detect lane lines on roads using Python and OpenCV. It leverages **Canny Edge Detection** and **Hough Transform** to identify and overlay lane lines in real-time on images or videos.

### 🔍 Features
- Detects left and right lane lines separately
- Uses smoothing across frames for stability
- Handles moderate lighting changes and curves
- Supports both images and videos

### 🛠️ Techniques Used
- Grayscale conversion and Gaussian blur
- Canny Edge Detection for edge filtering
- Region of Interest (ROI) masking
- Hough Line Transform to detect line segments
- Slope-based filtering to isolate lane lines
- Frame-to-frame smoothing for video

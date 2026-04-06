# Basic Image Operations

This module focuses on the fundamental concepts of image processing using Python and the OpenCV library. It covers the initial steps of handling image data, which are crucial for any computer vision task.

## Objective
To understand how to read, inspect, and visualize image data programmatically.

## Key Experiments

### 1. Image Loading and I/O
- Utilizing `cv2.imread()` to load images into the working environment.
- Handling different image formats and ensuring proper path referencing.

### 2. Inspecting Image Properties
Analysis of the underlying data structure of an image (NumPy array):
- **Shape**: Dimensions of the image (Height, Width, Channels).
- **Size**: Total number of pixels.
- **Data Type**: Memory representation of pixel values (typically `uint8`).

### 3. Image Visualization
- Using `cv2.imshow()` for windowed display.
- Integrating `matplotlib.pyplot` for inline visualization within Jupyter Notebooks, ensuring correct color channel ordering (BGR to RGB).

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- Matplotlib
- NumPy

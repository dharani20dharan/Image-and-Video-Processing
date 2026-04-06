# OpenCV Fundamentals

This directory contains practical implementations of core image processing functions using the OpenCV library. These experiments serve as the building blocks for more advanced computer vision applications.

## Objective
To master essential OpenCV operations including image manipulation, scaling, and color space transformations.

## Key Experiments

### 1. Familiarization with OpenCV (Experiment 1)
- **Reading and Displaying**: Loading images into the memory and rendering them as output.
- **Image Resizing**: Implementing interpolation techniques to scale images up or down while maintaining visual quality.
- **Grayscale Conversion**: Transforming standard BGR images into single-channel grayscale representations for simplified processing (e.g., edge detection, thresholding).

## Core Functions Used
- `cv2.imread()`: Input reading.
- `cv2.resize()`: Scaling operations.
- `cv2.cvtColor()`: Color space conversion (`COLOR_BGR2GRAY`).
- `cv2.imshow()` and `cv2.waitKey()`: Image output control.

## Files
- `OpenCV_basics.ipynb`: Documented implementation of the experiments.
- `image.JPG`: Sample dataset used for analysis.

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

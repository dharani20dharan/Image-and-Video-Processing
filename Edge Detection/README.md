# Edge Detection & HOG Feature Extraction

This project explores various techniques for extracting structural information from images, ranging from classical edge detection operators to modern feature descriptors like HOG.

## Overview

Edge detection is a fundamental tool in image processing, computing, and machine vision, particularly in the areas of feature detection and feature extraction. This experiment compares multiple gradient-based methods and implements a robust feature descriptor.

## Key Techniques

### 1. Classical Edge Detectors
- **Sobel Operator:** Computes the gradient of the image intensity at each point, giving the direction of the largest possible increase from light to dark.
- **Laplacian Operator:** A derivative operator which highlights regions of rapid intensity change.

### 2. Canny Edge Detection
A multi-stage algorithm used to detect a wide range of edges in images:
1. Noise Reduction (Gaussian filter)
2. Gradient Calculation
3. Non-maximum Suppression
4. Double Thresholding
5. Edge Tracking by Hysteresis

### 3. Histogram of Oriented Gradients (HOG)
The HOG descriptor focuses on the structure or the shape of an object. It is far better than any edge descriptor as it uses both magnitude as well as direction of the gradient to form the histogram.

## Dependencies

- **Python 3.x**
- **OpenCV:** For core image processing algorithms.
- **NumPy:** For high-performance array operations.
- **Matplotlib:** For visualizing the results.
- **Scikit-Image (`skimage`):** Frequently used for HOG implementation.

## Usage

1.  **Dependencies Installation:**
    ```bash
    pip install opencv-python numpy matplotlib scikit-image
    ```
2.  **Execution:**
    Run the `Edge Detection hog.ipynb` notebook to see the comparative analysis of different edge detection techniques and the visualization of HOG features on the sample images.

---
*Part of the Image and Video Processing Course Collection*

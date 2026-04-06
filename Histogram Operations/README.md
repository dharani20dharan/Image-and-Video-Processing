# Histogram Operations

This module explores the distribution of pixel intensities within images and techniques to enhance image contrast through statistical manipulation of the histogram.

## Objective
To understand image characteristics using histograms and to apply contrast enhancement techniques.

## Key Experiments

### 1. Histogram of an Image (Experiment 1)
- **Problem**: Computing and plotting the histogram of a grayscale image.
- **Theory**: A histogram represents the frequency distribution of pixel intensities (0–255).
- **Implementation**: Utilizing `cv2.calcHist()` or `plt.hist()` on the flattened NumPy array (`img.ravel()`).

### 2. Histogram Equalization (Experiment 2)
- **Problem**: Enhancing image contrast for low-contrast datasets.
- **Theory**: Redistribution of pixel intensities to span the entire available range (linearization of the cumulative distribution function).
- **Implementation**: Applying `cv2.equalizeHist()` to transform the image.

## Functions & Libraries
- `cv2.calcHist()`: Histogram computation.
- `cv2.equalizeHist()`: Global contrast enhancement.
- `matplotlib.pyplot`: Data visualization.

## Files
- `Histogram.ipynb`: Detailed Jupyter notebook with source code and visualizations.
- `image.png`: Test dataset for analysis.

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- Matplotlib
- NumPy

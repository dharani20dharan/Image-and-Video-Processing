# Wavelet Denoising & Deblurring

This experiment focuses on using Discrete Wavelet Transform (DWT) for image restoration, specifically targeting denoising and deblurring.

## Overview

Image denoising involves reducing noise while preserving important image features like edges. Wavelet transform is particularly effective because it allows for multi-resolution analysis, isolating noise in high-frequency components.

## Core Concepts

### 1. Discrete Wavelet Transform (DWT)
The image is decomposed into four sub-bands:
- **LL (Low-Low):** Approximation of the original image.
- **LH (Low-High):** Horizontal details.
- **HL (High-Low):** Vertical details.
- **HH (High-High):** Diagonal details.

### 2. Denoising via Thresholding
Noise predominantly resides in the high-frequency sub-bands (LH, HL, HH). By applying thresholding to these coefficients, we can filter out noise:
- **Hard Thresholding:** Sets coefficients below a certain value to zero.
- **Soft Thresholding:** Shrinks coefficients towards zero, providing smoother results.

### 3. Image Deblurring
The project also explores deblurring techniques using wavelets to sharpen edges and recover lost information.

## Dependencies

- **Python 3.x**
- **OpenCV:** Image reading and preprocessing.
- **NumPy:** Numerical operations.
- **PyWavelets (`pywt`):** Discrete Wavelet Transform implementation.
- **Matplotlib:** Visualization of results.

## Getting Started

1. Ensure all dependencies are installed:
   ```bash
   pip install opencv-python numpy PyWavelets matplotlib
   ```
2. Open and run the Jupyter Notebook `Wavelets and deblurring.ipynb` to see the results of the transformation and denoising.

---
*Part of the Image and Video Processing Course Collection*

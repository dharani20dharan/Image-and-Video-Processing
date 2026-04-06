# Image Filtering and Transformation Experiments

This folder contains implementations of spatial and frequency domain filtering techniques for image enhancement and noise reduction.

## Experiments Included

### 1. Gaussian Filtering
- **Objective**: Apply a Gaussian filter to smooth an image and reduce high-frequency noise.
- **Core Principle**: Uses a 2D Gaussian distribution as a point-spread function to perform weighted averaging of pixel neighborhoods.

### 2. Frequency Domain Low-Pass Filtering
- **Objective**: Implement low-pass filtering in the frequency domain.
- **Process**:
    - Transformation of the spatial image into the frequency domain using **Discrete Fourier Transform (DFT)**.
    - Application of a filter mask to attenuate high-frequency components.
    - Reconstruction of the image using **Inverse Discrete Fourier Transform (IDFT)**.

### 3. Median Filtering
- **Objective**: Perform non-linear filtering to remove impulsive noise.
- **Application**: Specifically used for removing **Salt and Pepper noise** while maintaining edge sharpness more effectively than linear smoothing filters.

## Project Structure
- `DCT.ipynb`: contains the complete Python implementation and visualization of results.
- `image.jpg`: The input source image used across all experiments.

## Prerequisites
To run these experiments, ensure you have the following Python libraries installed:
```bash
pip install opencv-python numpy matplotlib
```

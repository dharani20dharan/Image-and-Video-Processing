# SIFT Feature Matching & 3D Reconstruction

This project demonstrates the detection and matching of local features using the Scale-Invariant Feature Transform (SIFT) algorithm, a foundational technique in computer vision for image matching and 3D reconstruction.

## Overview

SIFT keypoints are particularly useful because they are invariant to image scale and rotation, and provide robust matching across a substantial range of affine distortion, change in 3D viewpoint, addition of noise, and change in illumination.

## Key Features

- **Keypoint Detection:** Identifying stable interest points across different scales using Difference of Gaussians (DoG).
- **Descriptor Generation:** Creating a unique fingerprint for each keypoint based on local gradient orientations.
- **Feature Matching:** Using Brute-Force or FLANN-based matchers to find correspondences between two different views of a scene.
- **Visualization:** Plotting the identified matches to verify the accuracy of the feature detection and matching process.

## Dependencies

- **Python 3.x**
- **OpenCV (cv2):** For SIFT implementation and image processing.
- **NumPy:** For efficient array manipulations.
- **Matplotlib:** For high-quality result visualization.

## Getting Started

1.  **Environment Setup:**
    ```bash
    pip install opencv-python numpy matplotlib
    ```
2.  **Run the Experiment:**
    Open the `SIFT 3D Reconstruction.ipynb` Jupyter notebook and execute the cells to see the feature matching in action using the provided sample images (`image1.jpeg` and `image2.jpeg`).

---
*Part of the Image and Video Processing Course Collection*

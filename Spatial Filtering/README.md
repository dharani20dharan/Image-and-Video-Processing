# Spatial Filtering: Convolution & Correlation

This module explores spatial neighborhood operations for image modification and statistical verification of the Central Limit Theorem.

## Objective
To understand and implement spatial filtering techniques (Convolution/Correlation) and demonstrate fundamental probability concepts in image processing contexts.

## Key Experiments

### 1. Spatial Filtering using Convolution (Experiment 1)
- **Problem**: Applying convolution to an image using custom filters.
- **Theory**: Sliding a kernel over an image and calculating weighted sums for blurring, sharpening, or edge detection.
- **Implementation**: Practical demonstration of kernel applications using numerical operations.

### 2. Image Correlation (Experiment 2)
- **Problem**: Differentiating and implementing correlation versus convolution.
- **Theory**: Correlation is a sliding dot product of a kernel with an image (unlike convolution, it does not involve flipping the kernel).
- **Implementation**: Using `cv2.filter2D()` to observe local similarities.

### 3. Verification of Central Limit Theorem (Experiment 3)
- **Problem**: Verifying CLT through random sampling.
- **Theory**: CLT states that the distribution of sample means of independent random variables approaches a normal distribution as the sample size increases.
- **Implementation**: Generating uniform random variables and visualizing their mean distribution via histograms.

## Functions & Libraries
- `cv2.filter2D()`: General spatial filtering.
- `np.random.uniform()`: Generating random test data.
- `matplotlib.pyplot`: Visualizing filtering results and probability distributions.

## Files
- `Convolution_Correlation.ipynb`: Comprehensive notebook for filtering and statistical analysis.
- `image.jpg`: Test dataset for filtering.

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- Matplotlib
- NumPy

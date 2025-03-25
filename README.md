# Image and Video Analytics

Assignment work done for the **CS1604** (Image and Video Analytics) course of our 6th Semester.

## Table of Contents

- [Image and Video Analytics](#image-and-video-analytics)
  - [Table of Contents](#table-of-contents)
  - [Aim](#aim)
  - [Assignments](#assignments)
  - [References](#references)

## Aim

The primary goal of this repository is to store and document all the assignments completed for the Image and Video Analytics course. The assignments are implemented in Jupyter notebooks, utilizing libraries such as OpenCV, SciPy, NumPy, and Matplotlib for various image and video processing tasks. This repository serves as a practical collection of the techniques and methods learned throughout the course.

## Assignments

- [03/01/2025: **Basic Image Manipulation**](/notebooks/03_01_2025_basic_manipulation.ipynb)
  - Displaying image properties
  - Calculation of megapixel count
  - Conversion to grayscale
  - Basic brightness manipulation

- [07/01/2025: **Image Processing - Point, Histogram, Mask Techniques**](/notebooks/07_01_2025_point_histogram_mask_processing.ipynb)
  - Thresholding
  - Point processing techniques:
    - Negative
    - Log
    - Inverse Log
    - Power Law (GAMMA)
    - Contrast Stretching
    - Gray Level Slicing
    - Bit Plane Slicing
  - Histogram processing techniques:
    - Equalization
    - Specification
  - Mask processing techniques:
    - Linear Smoothing (Normal, Weighted)
    - Median Filtering
    - Sharpen Filtering

- [17/01/2025: **Fourier Transform, Filters**](/notebooks/17_01_2025_fft_filters.ipynb)
  - Application of Fast Fourier Transform (FFT)
  - Application of Low, High and Band pass filters:
    - Ideal
    - Butterworth
    - Gaussian
    - Laplacian
    - Difference of Gaussian

- [04/02/2025: **Discrete Cosine Transform**](/notebooks/04_02_2025_dct_swapping_phases.ipynb)
  - Application of Discrete Cosine Transform (DCT)
  - Compression of image via DCT
  - Swapping phases of two images via FFT

- [11/02/2025: **Image Restoration, Segmentation, Morphological Operations**](/notebooks/11_02_2025_restoration_segmentation_morph_operations.ipynb)
  - Application of image degradation / restoration techniques:
    - Inverse Filtering
    - Wiener Deconvolution
    - Constrained Least Square
  - Segmentation techniques:
    - Point Detection
    - Line Detection
    - Edge Detection (Sobel, Prewitt, Canny, Laplacian of Gaussian (LoG))
    - Histogram Based Thresholding (Manual, Automatic, Optimal (Otsu))
  - Morphological operations:
    - Dilation
    - Erosion
    - Open
    - Close
    - Perimeter

- [18/02/2025: **Corner Detection, Feature Descriptors**](/notebooks/18_02_2025_corner_detection_feature_descriptors.ipynb)
  - Corner detection techniques:
    - Harris Corner Detection
    - Shi-Tomasi Corner Detection
  - Visual features matching:
    - Scale-Invariant Feature Transform (SIFT)
    - Oriented FAST and Rotated BRIEF (ORB)

- [25/02/2025: **Template Matching**](/notebooks/25_02_2025_template_matching.ipynb)
  - Comparison of template matching methods in OpenCV

- [10/03/2025: **Image Stitching, Face Detection**](/notebooks/10_03_2025_stitching_face_detection.ipynb)
  - Homography via RANSAC algorithm
  - Creation of stitched image via smooth merging of transformed images
  - Face detection via Cascade Classifiers (Haar Features, Viola-Jones algorithm)

- [18/03/2025: **Object Tracking**](/notebooks/18_03_2025_background_subtraction_obj_detect_track.ipynb)
  - Via change detection:
    - Frame Difference
    - Background Subtraction (Average, Median)
  - Via Gaussian Mixture Model (GMM)
  - Position tracking via Kalman Filter

- [25/03/2025: **Optical Flow**](/notebooks/25_03_2025_optical_flow.ipynb)
  - Sparse Optical Flow - Lucas-Kanade Algorithm
  - Dense Optical Flow - Gunnar-Farneback Algorithm

## References

Links to relevant reference materials are present as comments in the above notebooks.

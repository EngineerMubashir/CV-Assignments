Computer Vision Assignment 01

## Overview

This project is a **Computer Vision Assignment** that demonstrates the creation of a **hybrid image** by combining low-frequency and high-frequency components of two input images. It leverages foundational image processing techniques such as Gaussian blurring and image arithmetic.

---

## Objectives

- To understand and apply image filtering techniques, including **low-pass** and **high-pass** filters.
- To create a hybrid image that visually integrates features of two images.
- To use Python libraries like OpenCV and Matplotlib for image processing and visualization.

---

## Features

1. **Image Input:**
   - Allows users to upload two images (e.g., of group members).
   - Images are processed in grayscale for simplicity.

2. **Image Preprocessing:**
   - Resizes the uploaded images to a standard dimension of 500x500 pixels.

3. **Filtering Operations:**
   - **Low-Pass Filter:** A Gaussian Blur is applied to extract smooth, low-frequency components from the first image.
   - **High-Pass Filter:** High-frequency details are extracted from the second image by subtracting a blurred version of the image from the original.

4. **Hybrid Image Creation:**
   - Combines the low-pass filtered image and the high-pass filtered image to generate a hybrid image.

5. **Visualization:**
   - Displays the original, filtered, and hybrid images for comparison using Matplotlib.

---

## Dependencies

The following Python libraries are required:

- **OpenCV**: For image processing.
- **NumPy**: For numerical operations.
- **Matplotlib**: For image visualization.

To install the dependencies, run:

```bash
pip install opencv-python-headless numpy matplotlib
```

---

## How to Run

1. **Upload Images:**
   - Run the code and upload the required images when prompted. The first image is for the low-pass filter, and the second is for the high-pass filter.

2. **View Results:**
   - The script will process the images and display:
     - Original images
     - Low-pass and high-pass filtered images
     - Final hybrid image

---

## Code Structure

### Main Steps:

1. **Import Required Libraries**
2. **Image Upload and Preprocessing**
   - Resize images to 500x500 pixels.
3. **Apply Filters**
   - Gaussian blur for low-pass filtering.
   - Image subtraction for high-pass filtering.
4. **Combine Filters**
   - Weighted addition of filtered images.
5. **Display Results**

---

## Results

The hybrid image combines the dominant features of one image (low-frequency) with the fine details of another (high-frequency), creating a unique visual effect.

---

## Author

- **Group Members:** Add your names here.
- **Assignment Title:** Assignment 01 – Computer Vision

---

## Acknowledgments

- **Instructor:** [Instructor's Name]
- **Course:** Computer Vision – Software Engineering Program

---

Let me know if you'd like any modifications or additional sections!

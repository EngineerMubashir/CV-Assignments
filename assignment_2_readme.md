# README for Computer Vision Assignment 02

## Overview

This project implements **Harris Corner Detection**, a popular feature detection algorithm in computer vision. It identifies and highlights corners in an image by analyzing the intensity variations in multiple directions.

---

## Objectives

- To understand the Harris Corner Detection algorithm and its components.
- To implement corner detection using OpenCV and NumPy.
- To visualize and analyze corner detection results on uploaded images.

---

## Features

1. **Image Input:**
   - Users can upload an image to be processed.

2. **Preprocessing:**
   - Converts the image to grayscale to simplify gradient calculations.

3. **Gradient Calculation:**
   - Computes gradients in x and y directions using the Sobel operator.

4. **Second-Order Gradients:**
   - Calculates second-order gradient products (Ixx, Iyy, Ixy) and applies Gaussian blurring for smoothing.

5. **Harris Response Matrix:**
   - Computes the Harris response matrix to identify corner strengths.

6. **Corner Detection:**
   - Detects corners by applying a threshold to the Harris response matrix.

7. **Visualization:**
   - Marks detected corners on the original image and displays the result.

---

## Dependencies

The following Python libraries are required:

- **OpenCV:** For image processing.
- **NumPy:** For numerical operations.
- **Matplotlib:** For visualization.

To install the dependencies, run:

```bash
pip install opencv-python-headless numpy matplotlib
```

---

## How to Run

1. **Upload Image:**
   - Run the script and upload an image when prompted.
   - ![images](https://github.com/user-attachments/assets/3d8e483b-589b-46f9-991d-c68528c91c2d)


2. **View Results:**
   - The program will process the image and display:
     - The original image.
     - Detected corners marked on the image.

---

## Code Structure

### Main Steps:

1. **Import Required Libraries**
2. **Image Upload and Grayscale Conversion**
3. **Gradient Calculation**
   - Compute gradients using the Sobel operator.
4. **Gaussian Smoothing**
   - Smooth the second-order gradients (Ixx, Iyy, Ixy).
5. **Harris Response Calculation**
   - Derive the Harris response matrix.
6. **Corner Thresholding**
   - Apply a threshold to detect strong corners.
7. **Display Results**
   - Overlay detected corners on the original image and display it.

---

## Results

The program highlights corners in the uploaded image by marking them in the original image. This is useful for applications such as feature matching, object recognition, and motion tracking.

![image](https://github.com/user-attachments/assets/35292179-16cc-4c8b-af4c-0a4b66ae5b61)

## Author

- **Author:**  Muhammad Mubashir
- **Assignment Title:** Assignment 02 – Computer Vision

## Acknowledgments

- **Instructor:** Engr Ahmed Khawaja
- **Course:** Computer Vision – Software Engineering Program

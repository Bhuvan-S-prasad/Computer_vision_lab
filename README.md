# Image Processing with OpenCV

This project demonstrates various image processing techniques using OpenCV and Python, focusing on methods like edge detection, blurring, and frequency domain analysis. Each technique is essential for image enhancement, analysis, and understanding fundamental computer vision tasks.

## Table of Contents
- Libraries Used
- Requirements
- Image Processing Techniques
  - 1. Canny Edge Detection
  - 2. Sobel Edge Detection
  - 3. Gaussian Blur
  - 4. Gabor Filter
  - 5. Laplacian Edge Detection
  - 6. Frequency Domain Analysis (Fourier Transform)

---

## Libraries Used

- **OpenCV**: For handling various image processing operations.
- **NumPy**: To manage arrays and perform mathematical operations efficiently.
- **Matplotlib**: To visualize images and results of each processing technique.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

To install dependencies:
```bash
pip install opencv-python numpy matplotlib
```

## Image Processing Techniques

 ### Canny Edge Detection
- Canny edge detection is a multi-stage edge detection algorithm, widely used for detecting edges by identifying areas of intensity gradients in an image. It is highly effective in capturing edges while reducing noise.

### Sobel Edge Detection
- Sobel edge detection computes gradients along the x and y directions, allowing us to detect edges and the gradient orientation. This technique is particularly useful in applications requiring the direction of edge changes.

###  Gaussian Blur
- Gaussian blurring smooths the image by averaging pixel values, which helps to reduce noise and detail. It’s commonly used as a pre-processing step before edge detection to eliminate high-frequency noise.

### Gabor Filter
- The Gabor filter is used for texture analysis and edge detection, applying different orientations to detect edges or textures at specified angles. It is useful in applications where edge orientation is important, like texture classification.

### Laplacian Edge Detection
- Laplacian edge detection uses the second derivative of intensity values to highlight regions of rapid change. It is sensitive to noise, so applying a Gaussian blur beforehand is common to achieve better results.

### Frequency Domain Analysis (Fourier Transform)
- Fourier Transform converts an image from the spatial domain to the frequency domain, making it possible to analyze and manipulate various frequency components. This analysis is essential in filtering and compression applications, where the focus may be on certain frequency bands.

![](/img/48zd8xe6k49a1.jpg.png)
# JWST Image Analysis Project

## Overview
This project leverages images from the **James Webb Space Telescope (JWST)** for advanced astronomical analysis. It focuses on:
1. **Star Counting**: Using preprocessing techniques (filters, thresholding) and object/border detection algorithms (e.g., Canny, rectangle detection) for precise stellar quantification.
2. **Uncertainty Estimation**: Employing robust statistical methods to predict posteriors and uncertainties.

The project also includes a future perspective on using the **GaMPEN convolutional neural network** to decode galaxy morphological parameters, enabling deeper insights into galactic structure and evolution.

---

## Key Objectives
### 1. **Star Counting**
- Preprocessing with filters and thresholding.
- Object and edge detection using algorithms like:
  - **Canny Edge Detection**
  - **Rectangle Detection**
- Goal: Improve star identification accuracy.

### 2. **Uncertainty Estimation**
- Utilize statistical methods to compute posteriors.
- Deliver robust predictions for uncertainty in detected objects.

### 3. **Future Work: Galaxy Morphology Analysis**
- Implement **GaMPEN CNN** for analyzing galaxy morphology.
- Enable research on galactic structures and their evolution.

---

## Features
- Preprocessing pipelines for JWST images.
- Classical object detection algorithms.
- Statistical modeling for uncertainty estimation.
- Forward-looking implementation of CNNs for galaxy analysis.

---

## Technologies Used
- **Programming Language:** Python
- **Libraries & Tools:**
  - **OpenCV**: Image processing and edge detection.
  - **NumPy, SciPy**: Numerical computations and statistics.
  - **Matplotlib**: Data visualization.
  - **TensorFlow/PyTorch**: For future work on galaxy analysis.

---

#### References:

- Patrick Hébert Denis Laurendeau, Traitement des images , Université LAVAL.
- https://github.com/KouroshKSH/Astrophysical-Image-Processing-Using-JWST

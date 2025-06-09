# CS5720 - Neural Networks and Deep Learning  
### Home Assignment 2 – Summer 2025  
**Student Name:** Dasari Vineela
**Student Id:** 700777731
**University of Central Missouri**  
**Course:** CS5720 Neural Networks and Deep Learning  

---

## Assignment Overview

This repository contains three key machine learning and deep learning tasks implemented using **NumPy**, **TensorFlow/Keras**, **OpenCV**, and **Scikit-learn**. 

The aim is to demonstrate foundational concepts like: 
1. Convolution feature extraction.
2. Pooling.
3. Data preprocessing techniques.


---

## 1: Convolution Operations with Different Parameters**

**Goal:** Demonstrate how stride and padding affect convolution output using a 5×5 matrix and a 3×3 kernel.

- **Operations performed:**
  - Stride = 1, Padding = 'VALID'
  - Stride = 1, Padding = 'SAME'
  - Stride = 2, Padding = 'VALID'
  - Stride = 2, Padding = 'SAME'
  
**Tools used:** TensorFlow/Keras and NumPy

---

## 2.1: Edge Detection using Convolution

- Load a grayscale image using OpenCV
- Apply **Sobel filter** for:
  - Edge detection in X-direction
  - Edge detection in Y-direction
- Display:
  - Original image
  - Edge-X image
  - Edge-Y image

**Libraries:** OpenCV, NumPy, Matplotlib

## 2.2: Max and Average Pooling

- Create a random 4x4 matrix
- Apply:
  - 2x2 Max Pooling
  - 2x2 Average Pooling
- Print all matrices for comparison

**Libraries:** TensorFlow/Keras

---

## 3: Data Preprocessing - Normalization vs. Standardization**

**Steps:**

1. Load the **Iris dataset**
2. Apply:
   - **Min-Max Normalization**
   - **Z-score Standardization**
3. Visualize all three datasets (original, normalized, standardized) using histograms.
4. Train **Logistic Regression** on:
   - Raw data
   - Normalized data
   - Standardized data
5. Compare accuracy scores
6. Explain which scaling method to use for deep learning.

**Libraries:** Pandas, Matplotlib, Scikit-learn

---
# How to Run

```bash
# 1. Clone the Repository
git clone <NeuralNetworking-HomeAssignment2>
open n-n-home-asignment-1/Dasarivineela_NeuralNetworking-HomeAssignment2.ipynb

# 2. Run the each Python Scripts cell

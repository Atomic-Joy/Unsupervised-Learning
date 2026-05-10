# 🔢 PCA Visualization of Handwritten Digits

## Overview

This project demonstrates Dimensionality Reduction using Principal Component Analysis (PCA), which is a type of Unsupervised Learning used to reduce high-dimensional data while preserving important patterns and variance. In this project, the handwritten digits dataset from Scikit-learn is transformed from 64 dimensions into 2 dimensions for visualization and pattern analysis.

---

## Objective

To reduce high-dimensional handwritten digit image data into lower dimensions and visualize hidden structures, clusters, and relationships between different digit classes.

---

## Dataset

* Dataset: Digits Dataset
* Source: Scikit-learn
* Number of Classes: 10 (Digits 0–9)

### Features

* Pixel intensity values of handwritten digit images
* Each image size: 8 × 8 pixels
* Total Features: 64

### Target Labels

* Digit classes from 0 to 9

---

## Workflow

### 🔹 Data Loading

* Loaded the Digits dataset using Scikit-learn
* Extracted feature matrix and target labels

### 🔹 Data Exploration

* Checked dataset shape
* Observed feature dimensions
* Analyzed digit classes

### 🔹 Dimensionality Reduction

* Applied PCA (Principal Component Analysis)
* Reduced dimensions from 64 to 2
* Preserved maximum variance from original data

### 🔹 Visualization

* Generated 2D scatter plot using PCA components
* Colored points based on digit labels
* Visualized clustering patterns among digits

### 🔹 Variance Analysis

* Plotted explained variance ratio
* Measured information retained by principal components

---

## Model / Technique Used

### Principal Component Analysis (PCA)

* Unsupervised dimensionality reduction technique
* Reduces computational complexity
* Preserves important variance in data
* Helps visualize high-dimensional datasets
* Useful for preprocessing and feature extraction

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

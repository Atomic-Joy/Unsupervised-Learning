# 📊 Density Estimation using Kernel Density Estimation (KDE) — Portfolio Project

Built an **unsupervised machine learning density estimation system** using the Banknote Authentication Dataset to analyze and estimate the probability distribution of numerical data. Since density estimation does not require labeled predictions during training, the model focuses on identifying how data points are distributed across the feature space.

The model analyzes data using:

* Probability density estimation
* Distribution analysis techniques
* Gaussian Kernel functions

This project demonstrates how unsupervised learning can model continuous data distributions and identify regions of high and low data concentration.

---

## Objective

To estimate the probability density distribution of banknote feature data using Kernel Density Estimation (KDE) and visualize the underlying data distribution patterns.

---

## Approach

### 🔹 Data Analysis

* Explored dataset structure and numerical feature distributions
* Analyzed the variance feature for density estimation
* Visualized data distribution using histograms and density curves

### 🔹 Feature Engineering

* Selected numerical features from the dataset
* Applied **feature scaling (StandardScaler)**
* Prepared data for KDE model training

### 🔹 Model Development

Implemented:

* Kernel Density Estimation (KDE)
* Gaussian Kernel

### 🔹 Density Visualization

Generated:

* Histogram plots
* Density estimation curves

to analyze the probability distribution of the dataset.

---

## Evaluation

### 🔹 Density Estimation Analysis

The KDE model estimates the underlying probability density function of the data.

* High peaks → regions with high data concentration
* Low peaks → sparse data regions
* Smooth curves → continuous probability distribution

The visualization clearly demonstrates the distribution behavior of the selected feature.

---

## Key Results

* Successfully estimated the probability density distribution of the dataset
* Visualized continuous data distribution using KDE
* Identified regions of high and low data concentration
* Demonstrated practical implementation of density estimation techniques

---

## Visual Insights

* Histogram visualization showed feature distribution patterns
* KDE curves provided smooth probability density estimation
* Feature scaling improved model stability
* Density plots helped analyze data concentration behavior

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Algorithms Used

* Kernel Density Estimation (KDE)
* Gaussian Kernel
* StandardScaler
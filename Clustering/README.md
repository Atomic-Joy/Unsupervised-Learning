# 🧪 Glass Dataset Clustering using K-Means — Portfolio Project

Built an **unsupervised machine learning clustering system** using the Glass Identification Dataset to group glass samples based on their chemical composition. Since the dataset does not require target labels during training, clustering techniques are used to discover hidden structures and similarities within the data.

The model groups glass samples using:

* Chemical composition features
* Similarity-based clustering
* Pattern discovery techniques

This project demonstrates how unsupervised learning can identify meaningful groups without predefined labels.

---

## Objective

To analyze chemical properties of glass samples and automatically group similar glass types using clustering algorithms.

---

## Approach

### 🔹 Data Analysis

* Explored dataset structure and feature distributions
* Analyzed relationships between chemical components
* Visualized clustering behavior using scatter plots

### 🔹 Feature Engineering

* Removed unnecessary columns
* Applied **feature scaling (StandardScaler)**
* Prepared numerical features for clustering

### 🔹 Model Development

Implemented:

* K-Means Clustering
* PCA (Principal Component Analysis)

### 🔹 Cluster Optimization

Used:

* Elbow Method
* Silhouette Score analysis

to determine the optimal number of clusters.

---

## Evaluation

### 🔹 Silhouette Score

Measures how well-separated clusters are.

* Score close to **1** → strong clustering
* Score near **0** → overlapping clusters
* Negative score → poor clustering

Final optimized score:

* **Silhouette Score ≈ 0.44**

---

## Key Results

* Successfully grouped glass samples into meaningful clusters
* Achieved improved cluster separation after optimization
* PCA visualization showed clear cluster structures
* Determined optimal cluster count using evaluation metrics

---

## Visual Insights

* PCA reduced high-dimensional data into 2D space
* Cluster visualization revealed grouping patterns
* Feature scaling significantly improved clustering performance
* Elbow Method helped identify optimal cluster count

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## Impact

* Demonstrates understanding of **unsupervised learning workflows**
* Shows practical implementation of **clustering techniques**
* Highlights skills in:
  * Feature scaling
  * Cluster evaluation
  * Dimensionality reduction
  * Data visualization

---

## Algorithms Used

* K-Means Clustering
* PCA (Principal Component Analysis)
* StandardScaler

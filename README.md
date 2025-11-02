# PCA from Scratch 🧠

This repository contains a Jupyter Notebook that implements **Principal Component Analysis (PCA)** from scratch using **NumPy** and visualizes its results with **Matplotlib**. It also uses datasets from **scikit-learn** to demonstrate dimensionality reduction and feature extraction in real-world data.

## 📘 Notebook Overview

**File:** `PCA.ipynb`

This notebook walks through:
- Implementing PCA step-by-step without relying on `sklearn.decomposition.PCA`
- Computing eigenvalues and eigenvectors manually
- Projecting high-dimensional data into a lower-dimensional subspace
- Visualizing reconstructed data (e.g., faces dataset) to show information loss with reduced components

## 🧩 Key Features

- PCA algorithm built from scratch (no black-box library calls)
- Comparison with scikit-learn’s PCA implementation
- Visualization of eigenfaces and data reconstruction
- Demonstrations using:
  - `load_sample_images()` (color image data)
  - `fetch_lfw_people()` (face images dataset)
  - Synthetic datasets from `sklearn.datasets`

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib scikit-learn jupyter
```

## 📊 Example Output

- Scatter plots showing PCA projections  
- Eigenfaces reconstructed from reduced dimensions  
- Comparison of original vs. reconstructed images

## 🧠 Concepts Covered

- Mean centering and covariance matrix computation  
- Eigen decomposition and dimensionality reduction  
- Explained variance and component selection  
- PCA for image compression and face recognition  

**License:** MIT  
Feel free to use and modify this notebook for educational or research purposes.

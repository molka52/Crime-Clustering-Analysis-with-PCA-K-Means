## Crime Clustering Analysis with PCA & K-Means

This project explores crime data using unsupervised machine learning, combining PCA for dimensionality reduction and K-Means for clustering. The goal is to identify meaningful crime patterns and segment regions or crime types based on statistical behavior.

## 🔍 Project Overview

The notebook includes:

## 1. Data Exploration

Loading crimes.csv

Summary statistics and initial inspection

Boxplots and pairplots for anomaly and pattern detection

## 2. Correlation Study

Pearson correlation matrix

Annotated heatmap to understand variable relationships

## 3. Feature Engineering

Extraction of labels and numerical features

Standardization using StandardScaler

## 4. Principal Component Analysis (PCA)

Dimensionality reduction

Explained variance analysis

2D visualization of PCA components with annotated points

## 5. K-Means Clustering

Elbow method for selecting optimal cluster number

Clustering on:

Raw features

Scaled features

PCA-transformed features

Color-coded cluster visualizations

## 6. Cluster Profiling

Adding cluster labels to original dataset

Training a Decision Tree model to understand feature importance

Generating confusion matrix and accuracy metrics

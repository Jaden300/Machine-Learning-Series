# Unsupervised Learning Project

**Author:** J. Wong  
**Date:** 2026-03-10  

## Overview
This project explores **unsupervised and supervised learning techniques** on both **tabular and image datasets**, emphasizing **dimensionality reduction, clustering, visualization, and predictive modeling**. The main objectives are to uncover hidden patterns, reduce high-dimensional data into interpretable forms, and engineer features that improve model performance.

We use datasets such as the **[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)** and **[Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)** to demonstrate a variety of techniques, including:

- **Dimensionality Reduction:** `PCA`, `KernelPCA`, `t-SNE`  
- **Clustering:** `KMeans`, `DBSCAN`, `GaussianMixture`, `MeanShift`, `Agglomerative Clustering`  
- **Predictive Modeling:** `LogisticRegression` combined with cluster-based features  
- **Evaluation Metrics:** `ROC-AUC`, `Accuracy`  

Throughout the workflow, we emphasize **visual interpretability** using **scatter plots, 3D embeddings, cluster reconstructions, and feature importance visualizations**.

## Structure of the Notebook
The notebook is divided into the following sections:

1. **Imports & Preprocessing:** Standardizing features, encoding categorical variables, and subsampling data for efficiency.  
2. **KMeans Clustering:** Pixel-level clustering of images and feature clustering for tabular data.  
3. **Principal Component Analysis (PCA):** Dimensionality reduction and visualization of explained variance.  
4. **DBSCAN:** Density-based clustering to identify noise and discover clusters in t-SNE embeddings.  
5. **t-SNE:** Non-linear embedding for visualizing high-dimensional structures in 2D and 3D.  
6. **Mean Shift Clustering:** Identifying cluster centers and analyzing cluster-level feature statistics.  
7. **Agglomerative Clustering:** Hierarchical clustering with dendrogram visualizations.  
8. **Explained Variances & Feature Importance:** Evaluating PCA components and their contribution to feature representation.  
9. **Conclusion & Next Steps:** Summarizes insights and suggests potential improvements or extensions.

## Key Insights
- PCA and KernelPCA can compress high-dimensional data while retaining significant variance.  
- Clustering techniques reveal meaningful groupings in both tabular and image data.  
- t-SNE provides intuitive visualizations for complex, high-dimensional structures.  
- Cluster-based features can enhance predictive models like `LogisticRegression`.  
- DBSCAN and MeanShift effectively identify noise and natural clusters without specifying `n_clusters`.

## Next Steps
Future work could include:

- Experimenting with **other kernels in `KernelPCA`** or different distance metrics in clustering.  
- Scaling up the workflow to **full datasets** for more robust patterns.  
- Combining unsupervised embeddings with **deep learning models** for richer feature representations.  
- Evaluating **feature selection methods** to further improve model interpretability and performance.
# *Gaussian Mixture Model (GMM) vs K-Means Clustering*
This project explores unsupervised learning techniques — specifically K-Means and Gaussian Mixture Models (GMM) — applied to clustering tasks.
It includes model implementation, visualization, and performance comparison using PCA and t-SNE dimensionality reduction methods.

# *Project Overview*
A Gaussian Mixture Model (GMM) is a probabilistic model that assumes the data is generated from a combination of multiple Gaussian distributions.
Unlike K-Means, where each data point belongs to only one cluster, GMM performs soft clustering, assigning each point a probability of belonging to multiple clusters.

This project demonstrates:

How GMM can capture elliptical and overlapping clusters,

While K-Means creates hard, spherical clusters.

The differences are visualized with PCA (linear) and t-SNE (non-linear) methods.

# *Key Steps*
# 1-Data Preprocessing

Cleaning and normalizing the dataset

Handling categorical variables

# 2-Modeling

Applying K-Means and GaussianMixture from scikit-learn

Determining the optimal number of clusters using Elbow and Silhouette methods

# 3-Visualization

Dimensionality reduction using PCA and t-SNE

Visual comparison of cluster separations between K-Means and GMM

# 4-Evaluation Metrics

Silhouette Score

Davies–Bouldin Index

# *Technologies Used*
Python

Scikit-learn

Matplotlib / Seaborn

Pandas / NumPy

t-SNE / PCA

# *Conclusion:*
K-Means provides clear and simple partitions but lacks flexibility.

GMM offers a more realistic clustering structure when clusters overlap or are non-spherical.

PCA visualizations highlight overall separation, while t-SNE better reveals non-linear relationships.

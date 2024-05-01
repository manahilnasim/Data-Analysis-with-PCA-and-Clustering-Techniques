# Data Analysis with PCA and Clustering Techniques

## Project Overview
This project employs Principal Component Analysis (PCA) and various clustering techniques to explore and analyze a dataset of credit defaults. The goal is to identify patterns and groups within the data that may signify different risk levels for credit defaults.

## Contents
- Data preprocessing and exploration
- Implementation of PCA
- Hierarchical Clustering Analysis
- K-means Clustering Analysis
- Insights and Interpretation

## Objective
The primary objective is to utilize PCA to reduce dimensionality and apply clustering techniques to discover inherent groups within the dataset, providing insights into customer behaviors and risk profiles.

## Tools Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy

## How to Run the Notebook
1. Ensure Python and all required libraries are installed.
2. Download the dataset and place it in the designated directory.
3. Execute the notebook cells sequentially to reproduce the analysis.

## Analysis of Outputs

### Principal Component Analysis (PCA)
- **Variance Explained**: The first principal component accounts for approximately 21.97% of the variance, indicating a significant amount of information compressed into this component. The second principal component holds about 4.14%, with diminishing returns on explained variance for subsequent components.
- **Visualization**: The variance explained by each principal component was visualized in a bar chart, helping to assess the importance of each component in the dataset.

### Hierarchical Clustering
- **Dendrogram**: A dendrogram was constructed to visualize the data clustering based on hierarchical clustering. This visualization helps in determining the optimal number of clusters by observing the distance at which clusters are combined.
- **Cluster Map**: A cluster map was used to show the grouping of data points, offering a detailed look at the clusters' composition and distribution.

### K-means Clustering
- **Cluster Identification**: Three clusters were identified using the K-means algorithm, which was visualized using a scatter plot of the first two principal components.
- **Evaluation**: The choice of three clusters was initially based on domain knowledge, and further analysis, such as the silhouette score or the elbow method, might be required to confirm the optimal number of clusters.

## Insights and Future Work
- **Insights**: The clustering analysis provides insights into distinct groups within the credit default dataset, potentially corresponding to different risk levels. Understanding these groups can help in tailoring risk management strategies.
- **Future Work**: Future analyses could explore other clustering algorithms, increase the number of principal components used, or apply different scaling techniques to see how these affect the clustering outcomes.

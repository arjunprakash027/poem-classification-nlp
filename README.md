---
## View the medium blog here -> https://medium.com/@arjunprakash027/unveiling-the-poetic-patterns-journey-into-poem-classification-using-k-means-clustering-ec296984f071?source=friends_link&sk=fa8f1e3756663907ceb8c547ee8fb488
# Poetry Classification Using K-means Algorithm

Welcome to the Poetry Classification project, where we explore the fascinating world of clustering poems based on their themes and emotions using the K-means algorithm. This repository contains the code and insights from our exploration.

## Project Overview

In this project, we use the K-means algorithm to cluster poems based on their TF-IDF representations. The code provided here encompasses various stages of the project, from data preprocessing to clustering analysis.

## Code Explanations

### Preprocessing the Data

The provided code preprocesses the data by loading the dataset, dropping missing values, and extracting a subset of the data for analysis.

### Running K-means Clustering

The `run_Kmeans` function performs K-means clustering with varying numbers of clusters. It uses the `KMeans` algorithm from scikit-learn and stores the results in a dictionary.

### Silhouette Analysis

The `silhouette` function calculates the average silhouette score for each cluster configuration. It helps us determine the optimal number of clusters and visualize the quality of clustering.

### TF-IDF Vectorization

The code snippet related to TF-IDF vectorization transforms the poem text into a numerical format using the `TfidfVectorizer` from scikit-learn. This transformation captures the importance of words in each poem.

### Exploring Cluster Characteristics

The provided functions like `plotWords`, `centroidsDict`, and `plotWordCloud` allow us to visualize the dominant words and themes within each cluster. The `get_top_features_cluster` function extracts top features from clusters and visualizes them.

## Conclusion

Our exploration of poem classification through the K-means algorithm offers insights into the power of data-driven analysis in understanding the intricacies of poetic expression. By delving into clusters and visualizing word patterns, we bridge art and algorithm, unlocking emotions hidden within verses.

Feel free to explore the code and insights further. Join us on this journey as we celebrate the intersection of technology and creativity in the realm of poetry.

---

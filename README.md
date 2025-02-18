# Anxiety-Attack

## Overview
This project utilizes unsupervised learning techniques to analyze and predict the severity of anxiety attacks. The dataset includes information on various factors, such as demographics, lifestyle, psychological indicators, and physiological responses, which can help in understanding the factors contributing to anxiety attacks. By identifying patterns in these features, we aim to assess the risk and severity of anxiety attacks, potentially enabling early detection and intervention strategies.

## Models used

- KMeans Clustering : A centroid-based clustering algorithm that partitions the dataset into a predefined number of clusters. This model was used to categorize individuals into groups based on their anxiety severity.
  
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise):A density-based clustering algorithm that can identify clusters of arbitrary shapes and detect outliers. DBSCAN was used to find clusters of individuals with similar anxiety-related features and label any anomalies.

- Agglomerative Clustering: A hierarchical clustering method that builds a tree of clusters by iteratively merging the closest pairs of clusters. This approach helped in visualizing the relationships between individuals based on their anxiety-related attributes.

## Insights & Results

- K-Means provided distinct clusters based on stress levels, caffeine consumption, and physiological responses. We observed that individuals with higher stress and caffeine intake were more likely to be grouped in the high-risk category for severe anxiety attacks.

- DBSCAN identified some outliers who did not fit into any major clusters, which may represent individuals with unique or uncommon responses to stress or anxiety.

- Agglomerative Clustering provided a more granular view of the relationships between features, showing how factors like sleep hours and physical activity correlated with anxiety severity.

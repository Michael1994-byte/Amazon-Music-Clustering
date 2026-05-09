# Amazon Music Clustering

## Overview
This project uses KMeans Clustering to group similar songs based on audio features.

## Objective
To automatically cluster songs into meaningful groups using unsupervised machine learning.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Features Used
- danceability
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo
- duration_ms

## Workflow
1. Data Cleaning
2. Feature Selection
3. Feature Scaling
4. Elbow Method
5. KMeans Clustering
6. Cluster Evaluation
7. PCA Visualization
8. Cluster Interpretation

## Evaluation Metrics
- Silhouette Score: 0.238
- Davies-Bouldin Score: 1.57

## Results
The project successfully grouped songs into 3 clusters representing different musical characteristics and moods.

## Output
- Clustered CSV file
- PCA cluster visualization
- Cluster heatmap

## Conclusion
This project successfully grouped songs into meaningful clusters using KMeans clustering based on audio features. PCA visualization and evaluation metrics helped interpret cluster quality and song characteristics effectively.
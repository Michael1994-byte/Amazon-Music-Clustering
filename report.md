# Amazon Music Clustering Report

## Problem Statement
The goal of this project is to automatically group similar songs based on their audio characteristics using unsupervised machine learning techniques.

## Objective
To identify meaningful song clusters using audio features such as danceability, energy, loudness, acousticness, tempo, and valence.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Data loading
2. Data cleaning
3. Feature selection
4. Feature scaling using StandardScaler
5. Elbow Method
6. KMeans clustering
7. Cluster evaluation
8. PCA visualization
9. Cluster interpretation
10. CSV export

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

## Clustering Technique
KMeans clustering was used to group songs based on similarity in audio features.

## Evaluation Metrics
- Silhouette Score: 0.238
- Davies-Bouldin Score: 1.57

## Cluster Interpretation

### Cluster 0
Speech-heavy or spoken-content tracks with moderate energy.

### Cluster 1
Acoustic, calm, and instrumental tracks.

### Cluster 2
Energetic, upbeat, and high-tempo tracks.

## Visualizations
- Elbow Method graph
- Silhouette Score graph
- PCA cluster visualization
- Cluster heatmap

## Conclusion
The project successfully grouped songs into meaningful clusters using KMeans clustering. The results can be useful for music recommendation systems, playlist generation, and music discovery.
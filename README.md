# -K-Means-Clustering-on-Wine-Dataset

## Problem Statement
The objective of this project is to group wines into distinct clusters based on their chemical properties using the K-Means clustering algorithm without using predefined labels.

## Algorithm Used
K-Means Clustering (Unsupervised Learning)

## Dataset
- Wine Dataset (scikit-learn)
- Number of samples: 178
- Number of features: 13

## Steps Involved
1. Load the wine dataset
2. Perform feature scaling using StandardScaler
3. Apply K-Means clustering
4. Evaluate clustering using Silhouette Score
5. Visualize the clusters

## Evaluation Metric
- Silhouette Score

## How to Run
```bash
pip install -r requirements.txt
python kmeans.py


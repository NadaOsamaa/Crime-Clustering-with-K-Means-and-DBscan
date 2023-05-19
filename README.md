# Crime Clustering with K-Means and DB-Scan

This repository contains code for clustering crime data using K-Means and DB-Scan algorithms. The code is implemented in Python using the pandas, numpy, matplotlib, and scikit-learn libraries.

## Description

The goal of this project is to cluster crime data based on their geographical locations. Two clustering algorithms, K-Means and DB-Scan, are used to group crimes together based on their longitude and latitude coordinates. By clustering the crimes, we can identify patterns and gain insights into crime hotspots.

## Usage

The code consists of the following steps:

1. Import the necessary libraries: The required libraries are imported to perform data processing, visualization, and clustering.

2. Load the crime data: The crime data is loaded from a CSV file.

3. Perform data preprocessing and filtering: The data is filtered based on the desired crime type and any rows with missing longitude or latitude values are removed.

4. Apply K-Means clustering: The K-Means algorithm is used to cluster the data based on the longitude and latitude coordinates. The optimal number of clusters is determined using the Elbow method, and the clustering model is fitted to the data.

5. Visualize the clusters: The resulting clusters are visualized on a scatter plot, where each point represents a crime location and is colored based on its assigned cluster.

6. Evaluate the clustering using the Silhouette score: The Silhouette score is calculated to measure the quality of the clustering results. It indicates how well each data point fits within its assigned cluster.

7. Perform DB-Scan clustering: The DB-Scan algorithm is applied to the data to cluster crimes based on density. The clusters are identified based on the proximity of points to each other.

8. Visualize the DB-Scan clusters: The clusters obtained from DB-Scan are visualized on a scatter plot, similar to the K-Means visualization.

9. Evaluate the DB-Scan clustering using the Silhouette score: The Silhouette score is calculated to assess the quality of the DB-Scan clustering results.


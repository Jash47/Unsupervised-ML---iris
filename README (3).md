
# Prediction using Unsupervised ML ( iris ) 

This repository contains a project on prediction using unsupervised machine learning. The objective of the project is to use the Iris dataset to predict the optimum number of clusters and represent it visually.

### Dataset
The Iris dataset is a classic dataset in machine learning and is often used as a benchmark for clustering algorithms. It contains samples of iris flowers, with samples from each of three different species of iris (setosa, versicolor, and virginica). For each sample, four features are measured: sepal length, sepal width, petal length, and petal width.

### Predicting Optimum Number of Clusters : 
The optimum number of clusters was predicted using the elbow method. The elbow method involves plotting the within-cluster sum of squares (WCSS) against the number of clusters used in the k-means algorithm. The WCSS is the sum of the squared distance between each point and its assigned cluster center. The elbow method helps to identify the number of clusters at which the change in WCSS begins to level off.

In this project, the elbow method was applied to the Iris dataset and the optimum number of clusters was found to be three.

### Visual Representation of Clusters
After identifying the optimum number of clusters, k-means clustering was applied to the dataset with k=3. The resulting clusters were then visualized using a scatter plot. The scatter plot was created using the first two features (sepal length and sepal width) of the Iris dataset.

The scatter plot clearly shows the three clusters identified by the k-means algorithm. Each cluster is represented by a different color, and the centroids of the clusters are also shown. The visualization helps to easily understand the clustering results and how the data is grouped.

### Conclusion:
In this project, the optimum number of clusters for the Iris dataset was predicted using the elbow method and k-means clustering was applied to the dataset to group the samples into clusters. The resulting clusters were then visualized using a scatter plot. The project demonstrates the use of unsupervised machine learning techniques for clustering and visualizing data.

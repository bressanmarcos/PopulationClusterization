# PopulationClusterization

This project explores some of the tools provived by AWS Sagemaker.
The objective is to split a dataset into different clusters, so that somehow "similar" data points are grouped together.

In the studied dataset, I explore US Census data about american counties. Because of the huge number of features, I apply Principal Component Analysis in order to extract a smaller set of representative features. Afterward, I feed the transformed dataset into a K-Means model to find centroids and clusterize the counties.

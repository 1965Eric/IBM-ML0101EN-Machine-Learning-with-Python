## Module Introduction

In this module, you will learn about different clustering approaches. You will learn how to use clustering for customer segmentation, grouping same vehicles, and for weather stations. You will understand 3 main types of clustering including Partitioned-based Clustering, Hierarchical Clustering, and Density-based Clustering.

## Learning Objectives

* To understand different types of clustering algorithms.
* To apply clustering on different types of data sets.

## k-Means

[k-Means](https://github.com/1965Eric/IBM-ML0101EN-Machine-Learning-with-Python/blob/main/ML0101EN-Clus-K-Means-Customer-Seg.ipynb)

## Agglomerative Clustering

[Agglomerative Clustering](https://github.com/1965Eric/IBM-ML0101EN-Machine-Learning-with-Python/blob/main/ML0101EN-Clus-Hierarchical-Cars.ipynb)

## DBSCAN Clustering

[DBSCAN Clustering](https://github.com/1965Eric/IBM-ML0101EN-Machine-Learning-with-Python/blob/main/ML0101EN-Clus-DBSCN-weather.ipynb)

## Module 4 - Graded Quiz

Question 1: Which statement is NOT TRUE about k-means clustering?

- A. [ ] The objective of k-means, is to form clusters in such a way that similar samples go into a cluster, and dissimilar samples fall into different clusters.
- B. [ ] k-means divides the data into non-overlapping clusters without any cluster-internal structure.
- C. [X] As k-means is an iterative algorithm, it guarantees that it will always converge to the global optimum.

Question 2: Which of the following are characteristics of DBSCAN? (Select all that apply)

- A. [ ] DBSCAN does not require one to specify the number of clusters such as k in k-means.
- B. [ ] DBSCAN can find arbitrarily shaped clusters.
- C. [ ] DBSCAN can find a cluster completely surrounded by a different cluster.
- D. [ ] DBSCAN has a notion of noise, and is robust to outliers.
- E. [X] All of the above.

Question 3: Which of the following is an application of clustering?

- A. [ ] Customer churn prediction
- B. [ ] Price estimation
- C. [X] Customer segmentation
- D. [ ] Sales prediction

Question 4: Which approach can be used to calculate dissimilarity of objects in clustering?

- A. [ ] Cosine similarity
- B. [ ] Euclidian distance
- C. [ ] Minkowski distance
- D. [X] All of the above

Question 5: How is a center point (centroid) picked for each cluster in k-means? (Select all that apply)

- A. [X] We can randomly choose some observations out of the data set and use these observations as the initial means.
- B. [X] We can create some random points as centroids of the clusters.
- C. [ ] We can select it through correlation analysis.

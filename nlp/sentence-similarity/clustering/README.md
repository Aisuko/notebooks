# Clustering

> Clustering of unlabeled data can be performed with the module `sklearn.cluster`.

Each clustering algorithm comes in two variants: 

**A class**

It implements the `fit` method to learn the clusters on train data.

**A function**

It given train data, return an array of interger labels corresponding to the different clusters.

For the class, the labels over the training data can be found in the `label_` attribute.


## K-means

The K-Means algorithm clusters data by `trying to separate samples in n groups of equal variance`, `minimizing a criterion known as the inertia or within-cluster sum-of-squares(see below)`. This algorithm requires the number of clusters to be specified. It scales well to large number of samples and has been used across a lage range of application areas in many different fields.

The k-means algorithm divides a set of N samples X into K disjoint clusters C, each described by the mean $\mu_{j}$ of the samples in the cluster. The means are commonly called the cluster "centroids"; note that they are not, in general, points from X, although they live in the same space. 

The K-means algorithm aims to choose centroids that minimize the inertia, or within-cluster sum-of-squares criterion:

$$\sum_{i=0}^{n}\min_{\mu_{j} \in C}(||x_{i} - \mu_{j}||^{2})$$

Inertia can be recognized as a measure of how internally coherent clusters are. It suffers from various drawbacks:

- Inertia makes the assumption that clusters are convex and isotropic, which is not always the case. It responds poorly to elongated clusters, or manifolds with irregular shapes.
- Inertia is not a normalized metric: we just know that lower values are better and zero is optimal. But in very high-dimensional spaces, Euclidean distances tend to become inflated (this is an instance of the so-called "curse of dimensionality"). Running a dimensionality reduction algorithm such as PCA prior to k-means clustering can alleviate this problem and speed up the computations.

See an example of [K-means Clustering](https://www.kaggle.com/code/aisuko/k-means-clustering/notebook) on Kaggle.
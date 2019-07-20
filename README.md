# CustomerSegmentation_KMeansClustering-
Categorisation of Customers into clusters on the basis of Age, Income and Education  


K-Means clustering aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.

The model holds a vector of k centers and one of the distance metrics provided by the ML framework such as Euclidean, Hamming or Manhattan.

KMeans is a unsupervised learning algorithm. It solves a clustering task which is the task of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar (in some sense) to each other than to those in other groups (clusters).

KMeans is a parametrized iterative algorithm which calculates the new means to be the centroids of the observations in the clusters on each iteration.

Presently, Ignite supports a few parameters for the KMeans classification algorithm:

k - a number of possible clusters
maxIterations - one stop criteria (the other one is epsilon)
epsilon - delta of convergence (delta between old and new centroid's values)
distance - one of the distance metrics provided by the ML framework such as Euclidean, Hamming or Manhattan
seed - one of initialization parameters which helps to reproduce models (trainer has a random initialization step to get the first centroids)

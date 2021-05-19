# Task-2---Prediction-using-unsupervised-ml
From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually.


Unsupervised Learning~
Unsupervised learning is a machine learning algorithm that searches for previously unknown patterns within a data set containing no labeled responses and without human interaction. The most prominent methods of unsupervised learning are cluster analysis and principal component analysis.



use the scikit-learn library in Python to load the Iris dataset and matplotlib for data visualization.

K-MEANS CLUSTERING IN PYTHON
K-means clustering is an iterative clustering algorithm that aims to find local maxima in each iteration. Initially, desired number of clusters are chosen.
Based on the centroid distance between each point, the next given inputs are segregated into respected clusters and the centroids are re-computed for all the clusters.

Each centroid of a cluster is a collection of feature values which define the resulting groups. Examining the centroid feature weights can be used to qualitatively interpret what kind of group each cluster represent.

We import the k-means model from scikit-learn library, fit out features and predict.

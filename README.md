# Handwritten-Digits-Prediction-Project

* The data set i am going to use contains images of hand-written digits with 10 classes where each class refers to a digit.This is a copy of the test set of the UCI ML hand-written digits datasets.They are grouped into pixels.

## Steps to be followed:-
    
1.I will start by loading the digits dataset from sklearn datasets.
2.Import neccesary libraries that will be used in my dataset.
3.Define number of clusters, K, which need to be found out. 
4.Randomly select K cluster centroids.
5.For each observation, find out the euclidean distance between the observation and all the K cluster centers of all distances. 
6.Find the nearest distance between the observation and one of the K cluster centroids (cluster centers) and assign the observation to that cluster.
7.Move the K-centroids to the center of the points assigned to it and visualize. 
8.Repeat the above two steps until there is no change in the cluster centroids.
9.Finding K-Means Clustering using elbow method by optimizing K.

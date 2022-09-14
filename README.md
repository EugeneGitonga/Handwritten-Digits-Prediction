# Handwritten-Digits-Prediction-Project

## Contribute Code

Contributions are most welcome, whether you’ve fixed a bug or introduced a new feature in the notebook. I welcome pull requests! (If you’d like to make a larger change and check with me first, you can do so via (https://www.linkedin.com/in/eugene-gitonga-b29730163/).

## Introduction

* The data set I am going to use contains images of hand-written digits with 10 classes where each class refers to a digit. This is a copy of the test set of the UCI ML hand-written digits datasets. They are grouped into pixels.

## Steps to be followed:-
    
* I will start by loading the digits dataset from sklearn datasets.
* Import neccesary libraries that will be used in my dataset.
* Define number of clusters, K, which need to be found out. 
* Randomly select K cluster centroids.
* For each observation, find out the euclidean distance between the observation and all the K cluster centers of all distances. 
* Find the nearest distance between the observation and one of the K cluster centroids (cluster centers) and assign the observation to that cluster.
* Move the K-centroids to the center of the points assigned to it and visualize. 
* Repeat the above two steps until there is no change in the cluster centroids.
* Finding K-Means Clustering using elbow method by optimizing K.

## How to run this project from GitHub
### Method 1 : Using Binder
* MyBinder.org is a great project that allows you to create virtualized Jupyter Notebook environment from any GitHub repository. 
* You just need to enter the URL, and Binder will create a container for you, and start Jupyter environment. 
* Many repositories with Jupyter Notebooks include Launch Binder button to open the repository in Binder automatically.

![image](https://user-images.githubusercontent.com/70195777/190092838-4040c7f5-3b2a-46d4-979a-858b292de60f.png)

* Binder will try to setup an environment best suited for your needs.

### Method 2 : Using GitHub Codespaces
* GitHub Codespaces is a great feature of GitHub that allows you to open any repository in a virtualized environment in the cloud, and access it through either online VS Code editor in your browser, or through local VS Code installation. 
* Currently, you may sign up for beta access to Codespaces, which will include some free compute to run your notebooks on.

### Method 3 : Run it in your local Python environment
* You can download the notebook from my GitHub repository and run it in your local Python environment using either browser interface to Jupyter/JupyterLab, or Visual Studio Code.

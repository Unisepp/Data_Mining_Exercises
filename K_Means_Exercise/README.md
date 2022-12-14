# Clustering Iris Dataset


## Project Intro
The purpose of this project is to cluster the flowers in the Iris dataset using the K_Means algorithm from the clustering algorithms.

### Methods Used
* Data Preparation
* Machine Learning
* Visualization

### Technologies
* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)
* [Seaborn](https://seaborn.pydata.org/)

## Project Description
K-means is an Unsupervised algorithm and it will find patterns in the data. It will assign each data point randomly to some clusters then it will move the centroid of each cluster.This process will continue until the cluster variation with in the data can’t be reduced any further.

The Elbow method and Inertia which is the sum of squared distances of the samples to their closest cluster centre have been used to find the optimal number of clusters. 

The graph of WCSS: 

![here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/K_Means_Exercise/wcss.png)

Visualization methods have been used to demonstrate the final result of the clustering algorithm.

The plot of the clustering result:

![here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/K_Means_Exercise/Clusters%20of%20flowers.png)


## Getting Started

1. Download and install python on your computer
2. Make sure to install libraries that have been mentioned before in the 'Technologies' section of the text, if you don't already have them
3. You can either directly download this repo or clone it (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)) 
4. Dataset is being kept [here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/K_Means_Exercise/iris.csv)
5. Data transformation script is being kept [here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/K_Means_Exercise/K_means.py)
6. Run the code in python and see the results



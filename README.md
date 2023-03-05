# Customer-Segmentation-using-k-means
This project is a part of the SEMESTER 3 project at [Vellore Institute of Technology, Vellore](https://vit.ac.in/).

#### -- Project Status: [Completed]

## Overview 

The process of dividing the customer base into multiple groups based on shared characteristics that are relevant to marketing, such as gender, age, interests, and spending habits, is known as Customer Segmentation. In the initial stage of this data science project, we will conduct data exploration by importing essential packages, reading the data, and gaining insights into the input data.

#### K-Means Clustering:

The K-Means algorithm is an iterative approach used to segregate a dataset into K distinct, non-overlapping subgroups or clusters. It aims to ensure that each data point belongs to only one group, and that intra-cluster data points are as similar as possible, while inter-cluster points are as dissimilar as possible. To achieve this, the algorithm assigns data points to clusters such that the sum of the squared distance between the data points and the cluster's centroid is minimized. By reducing variation within clusters, data points within the same cluster become more homogeneous.

Afterward, we performed K-Means Clustering to group similar spending activity based on age and annual income into different clusters. This involved randomly selecting values from the data and assigning them to clusters. We then updated the cluster and re-shaped the plot using the closest values to the center of each cluster, similar to k-NN, based on the Euclidean Distance metric.


## Dependencies

* [Pandas](https://pandas.pydata.org/docs/)
* [NumPy](https://numpy.org/devdocs/user/index.html)
* [Matplotlib](https://matplotlib.org/3.3.3/contents.html)
* [Seaborn](https://seaborn.pydata.org/)
* [Sklearn](https://scikit-learn.org/stable/)



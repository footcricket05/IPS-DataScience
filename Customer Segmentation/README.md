# Customer-Segmentation-Using-K-Means

Customer Segmentation is the process of dividing a customer base into several groups of individuals that share similarities in different ways relevant to marketing such as age, gender, interests, and spending habits. In this data science project, we perform customer segmentation using K-Means clustering.

## Objective
The objective of this project is to segment customers based on their age and annual income into different clusters to identify similar spending patterns.

## Dataset
The dataset used in this project is a sample customer dataset containing customer information such as age, annual income, and spending score. 

Link- https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Approach
The approach used in this project is K-Means Clustering, which is an iterative algorithm that tries to partition the dataset into K pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid is at the minimum. We use the scikit-learn library in Python to perform K-Means clustering.

The steps involved in this project are:

1. Importing the necessary packages and reading the dataset.

2. Exploratory data analysis to gain insights about the dataset.

3. Preprocessing the data by scaling it using StandardScaler.

4. Determining the optimal number of clusters using the elbow method.

5. Performing K-Means clustering using the optimal number of clusters obtained in step 4.

6. Visualizing the clusters and analyzing the spending patterns of each cluster.


## Results
The optimal number of clusters obtained using the elbow method was 5. The K-Means clustering algorithm was applied to the dataset with 5 clusters, and the spending patterns of each cluster were analyzed.

## Conclusion
In conclusion, customer segmentation using K-Means clustering is an effective way to group customers with similar spending patterns. This can be used by businesses to target specific groups of customers with personalized marketing strategies.

# Repo for customer segmentation

1. Built a simple model to segment customers which can be used for target marketing.
2. Bank customer data was used.
3. Cleaned the data and performed EDA to get a better understanding of the data.
4. Autoencoders and PCA were used for dimensionality reduction and visualizations.


## Code and Resources Used

Python Version: 3.7

Packages: pandas, sklearn, matplotlib, seaborn, tensorflow.

## Model Building:

* Used K-means to cluster the customers. Optimum k value was found using Elbow method and Silhouette method.

* Got 7 clusters but required less cluters. So used Autoencoders to reduce the dimensions.

* Once again performed clustering using K-means. This time used optimum K-value as 3 based on elbow method and silhouette score.

* For vizualization purpose used PCA and reduced the features to two PCA components.

### Visualization of customer segmentation using PCA(7 clusters)

![alt text](https://github.com/Jishan-works/Customer-Segmentation-using-Kmeans/blob/master/cluster1.png)

### Visualization of customer segmentation using PCA(3 clusters)

![alt text](https://github.com/Jishan-works/Customer-Segmentation-using-Kmeans/blob/master/cluster2.png)



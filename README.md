Iris Clustering using K-Means and Hierarchical Clustering

Project Overview

This project focuses on applying Unsupervised Machine Learning techniques to the Iris dataset. The main objective is to group similar Iris flowers into clusters based on their measurements without using the species labels.

Dataset

The Iris dataset is obtained from the Scikit-learn library. It contains 150 samples and four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The species/target column is not used during clustering because this is an unsupervised learning problem.

Objectives

* Load and preprocess the Iris dataset.
* Standardize the numerical features.
* Apply K-Means Clustering.
* Determine the suitable number of clusters using the Elbow Method.
* Apply Hierarchical Clustering.
* Visualize the clusters and dendrogram.
* Compare the results of both clustering techniques.

Technologies Used

* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Scikit-learn
* SciPy

Methodology

1. Data Loading

The Iris dataset is loaded using the sklearn library.

2. Data Preprocessing

The species/target column is excluded from clustering, and the numerical features are standardized using StandardScaler.

3. K-Means Clustering

K-Means clustering is applied to group the Iris flowers into 3 clusters. The Elbow Method is used to determine the suitable number of clusters. Centroids are also visualized to understand the center of each cluster.

4. Hierarchical Clustering

Agglomerative Hierarchical Clustering is applied with 3 clusters. A dendrogram is created using the Ward linkage method to visualize the hierarchical grouping of the data.

5. Visualization and Comparison

The clusters are visualized using Petal Length and Petal Width. The results of K-Means and Hierarchical Clustering are compared to understand how both algorithms group the Iris data.

Key Insights

* K-Means successfully grouped the Iris dataset into 3 clusters.
* Petal Length and Petal Width provide clear separation between the clusters.
* The K-Means centroids represent the center of each cluster.
* The Hierarchical Clustering dendrogram shows how data points are progressively merged.
* Both clustering techniques identified meaningful groups in the Iris dataset.

Conclusion

The Iris dataset was successfully analyzed using K-Means and Hierarchical Clustering techniques. The Elbow Method indicated that three clusters were suitable for K-Means. Both methods identified meaningful groups based on the similarity of Iris flower features. Overall, clustering techniques were effective in discovering natural patterns in the dataset.

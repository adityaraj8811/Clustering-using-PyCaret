### Clustering-using-PyCaret

##Exploring the Comparative Performance of Clustering Algorithms with Diverse Pre-processing Techniques and Varied Cluster Counts across Multiple Evaluation Parameters
From the Datasets library of PyCaret, 'Wine Quality' dataset was chosen for the comparative performance of different Clustering Algorithms with number of clusters = 3,4,5.
Clustering Algorithms used were - K Means, Hierarchical and Agglomerative Clustering##

**Result Table**:

<img width="855" alt="Screenshot 2024-02-22 at 7 03 13 PM" src="https://github.com/adityaraj8811/Clustering-using-PyCaret/assets/91868945/a5b9fee5-22d8-4553-828a-4bdd35abe384">

**Table Analysis**:
1. In all the above Clustering Algorithms, we can conclude that using Transformation for pre-processing resulted in the best silouette score compared to all other forms of pre-processing.
2. Transformation increases the silhouette score while Normalization adversely affected the data, resulting in lower silhouette scores during clustering.
3. PCA didnt have any noticeable impact which implies that the reduction in dimensionality achieved through PCA did not distort the essential features of the data relevant for clustering, and the clustering results remained consistent before and after applying PCA.
4. In all clustering algorithms, K-means exhibited superior performance when paired with transformation preprocessing techniques.
5. When employing all preprocessing techniques, including transformation, normalization, and PCA, the silhouette score remained consistent with the scenario where only transformation and normalization were applied.

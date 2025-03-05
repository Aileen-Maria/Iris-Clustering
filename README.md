# Iris Clustering Project  

## Project Overview  
This project applies clustering techniques to the **Iris dataset** using **KMeans** and **Hierarchical Clustering**. The objective is to group similar data points without predefined labels and analyze how well clustering algorithms can separate the species.  

## Dataset  
The **Iris dataset** from `sklearn.datasets` consists of **150 samples** across three species (*Setosa, Versicolor, and Virginica*). Each sample has the following four features:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

Since this is an **unsupervised learning** task, the species labels are removed before clustering.  

## Clustering Methods  

### 1. KMeans Clustering  
- A centroid-based clustering algorithm that assigns data points to **K clusters** based on proximity to cluster centers.  
- The **Elbow Method** is used to determine the optimal number of clusters.  
- Results are visualized using scatter plots with distinct cluster assignments.  

### 2. Hierarchical Clustering  
- A clustering method that builds a hierarchy of clusters using **agglomerative clustering**.  
- A **dendrogram** is used to determine the number of clusters.  
- The final clusters are visualized using scatter plots.  

## Steps in Implementation  
1. Load and preprocess the **Iris dataset**.  
2. Apply **KMeans Clustering** and visualize results.  
3. Apply **Hierarchical Clustering** and visualize results.  
4. Compare the performance of both methods.  

## Tools & Libraries Used  
- Python  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Pandas  
- NumPy  

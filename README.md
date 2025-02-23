
## **Clustering Algorithms: K-Means, Hierarchical, DBSCAN, and GMM**  

### **Overview**  
Classical clustering algorithms are the backbone of unsupervised machine learning, designed to partition similar data points into clusters based on their characteristics. This repository contains implementations of four major clustering techniques:  

- **K-Means**: A partitioning algorithm that minimizes within-cluster variance and is best suited for well-separated spherical clusters.  
- **Hierarchical Clustering**: An algorithm that builds a tree-like structure of clusters, allowing a detailed understanding of relationships among clusters.  
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A density-based clustering method that identifies clusters of arbitrary shapes and effectively handles noise and outliers.  
- **Gaussian Mixture Model (GMM)**: A probabilistic model that assumes data points are generated from a mixture of Gaussian distributions, making it ideal for capturing complex cluster structures.  

Each of these techniques has been applied to different datasets, and their performance has been evaluated using the **Adjusted Rand Index (ARI)** to determine the best-suited algorithm for each dataset.  

---

### **Notebooks**  
This repository includes four Jupyter notebooks, each demonstrating a different clustering method:  

1. **`K-Means Clustering.ipynb`** - Implementation of K-Means clustering and evaluation across datasets.  
2. **`Heirarchical Clustering.ipynb`** - Application of hierarchical clustering (Agglomerative & Divisive) on datasets.  
3. **`Density-Based Spatial Clustering.ipynb`** - DBSCAN clustering applied to datasets with noise and complex shapes.  
4. **`Gaussian Mixture Model.ipynb`** - Gaussian Mixture Model clustering using probabilistic modeling.  

---

### **Datasets**  
The following datasets have been used to evaluate the clustering methods:  

- **`blob`**: A standard dataset with a blob-like distribution, ideal for testing clustering algorithms.  
- **`dart`**: A scattered, dartboard-like dataset to test cluster separation.  
- **`outliers`**: Includes outlier points to assess robustness against noisy data.  
- **`spiral2`**: A challenging dataset with a spiral pattern, testing K-Means' limitations.  
- **`basic2`**: A simple 2D dataset for evaluating basic clustering patterns.  
- **`boxes3`**: A dataset with distinct box-like cluster structures.  

---

### **Evaluation & Results**  
Each clustering algorithm has been evaluated based on its ability to correctly cluster data points, with **Adjusted Rand Index (ARI)** used as a key metric to measure clustering performance. The results provide insights into which method is best suited for different types of datasets.  


### **Conclusion**  
While **K-Means** is effective for well-separated clusters, **Hierarchical Clustering** provides better interpretability. **DBSCAN** performs well on datasets with noise and irregular shapes, while **GMM** is useful for complex, overlapping clusters. This project highlights the strengths and limitations of each method across different datasets.  

---

### **Author**  
- **Siya Simon**  

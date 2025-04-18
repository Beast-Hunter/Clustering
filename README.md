# 🧠 Clustering Algorithms on the Iris Dataset

This project performs a comparative analysis of multiple clustering algorithms using different preprocessing techniques and a range of cluster numbers on the popular **Iris dataset**.

---

## 📊 Objectives

- Compare clustering algorithms: **KMeans**, **Agglomerative Clustering**, and **Gaussian Mixture Model**
- Use preprocessing techniques: **Standardization**, **Normalization**, and **PCA**
- Evaluate performance using metrics:
  - **Silhouette Score**
  - **Calinski-Harabasz Score**
  - **Davies-Bouldin Score**
- Analyze results across different numbers of clusters (3 to 5)

---

## ⚙️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn` (datasets, clustering, preprocessing, decomposition, metrics)

---

## 📁 Dataset

- **Name:** Iris Dataset
- **Source:** UCI Machine Learning Repository
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Labels:** 3 flower species (used only for ARI comparison)

---

## 🔄 Preprocessing Techniques

| Technique      | Description                            |
|----------------|----------------------------------------|
| Standardization| Mean 0, Unit variance                   |
| Normalization  | Scales between [0, 1]                   |
| PCA            | Reduces data to 2 principal components |

---

## 🧪 Clustering Algorithms Tested

| Algorithm              | Description                                  |
|------------------------|----------------------------------------------|
| KMeans                 | Partitional clustering                       |
| Agglomerative Clustering | Hierarchical clustering                     |
| Gaussian Mixture Model | Probabilistic model-based clustering         |

---

## 📈 Evaluation Metrics

| Metric               | Meaning                                                  |
|----------------------|----------------------------------------------------------|
| Silhouette Score     | Cohesion vs separation                                  |
| Calinski-Harabasz    | Ratio of between-cluster dispersion to within-cluster   |
| Davies-Bouldin       | Measures average similarity between each cluster        |

---

### 📊 Example Result (Silhouette Scores, Cluster=3):

![ClusteringComparison](https://github.com/user-attachments/assets/686b9faf-bb69-4c3b-a6f1-c48c7a25a27d)

---

## 📁 Repository Contents


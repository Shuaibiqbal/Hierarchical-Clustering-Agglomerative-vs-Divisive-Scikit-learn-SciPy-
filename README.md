# Hierarchical Clustering: Agglomerative vs Divisive (Scikit-learn & SciPy)
A simple demonstration of Hierarchical (Agglomerative) Clustering using synthetic data, complete with dendrogram visualization and cluster interpretation.

This repository demonstrates the concept of **Hierarchical Clustering**, one of the fundamental unsupervised learning techniques used to build nested clusters. It covers both major types:

- **Agglomerative Clustering (Bottom-Up)** using `scikit-learn` and `scipy`
- **Divisive Clustering (Top-Down)** using a simulated approach via `KMeans`

---

## 📌 What is Hierarchical Clustering?

Hierarchical Clustering builds a hierarchy of clusters either by:

- **Merging (Agglomerative)**: Starts with individual points and merges them into clusters step by step.
- **Splitting (Divisive)**: Starts with all data in one cluster and splits it recursively.

This approach is often visualized using a **dendrogram**.

---

## 🧠 Techniques Implemented

### ✅ Agglomerative Clustering (Bottom-Up)
- Uses `scipy.cluster.hierarchy.linkage` and `dendrogram` for visualization
- Uses `sklearn.cluster.AgglomerativeClustering` to form final clusters
- Visualizes both the **dendrogram** and **cluster assignment**

### ✅ Divisive Clustering (Top-Down)
- Simulated via recursive **Bisecting KMeans**
- Splits the dataset into 2 clusters at each step (depth-controlled)
- Visualizes clusters at each stage of division

---

## 📊 Visualizations

- **Dendrogram** to show how clusters are formed step-by-step (Agglomerative)
- **Scatter plots** to visualize final cluster assignments for both approaches

---

## 🛠️ Libraries Used

- `scikit-learn`
- `scipy`
- `matplotlib`
- `numpy`

---

for more clearification open notebook 

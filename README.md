# Unsupervised_Learning

🌸 Unsupervised Learning on the Iris Dataset
K‑Means • Hierarchical Clustering • PCA • t‑SNE • Silhouette Analysis
This project demonstrates a complete unsupervised learning workflow using the classic Iris dataset. It includes preprocessing, cluster determination, multiple clustering algorithms, evaluation metrics, and rich visualizations (2D & 3D PCA, dendrograms, cluster plots).

📌 Project Overview
Unsupervised learning helps uncover hidden patterns in data without using labels.
In this project, we explore the Iris dataset using:

K-Means Clustering

Hierarchical (Agglomerative) Clustering

Elbow Method

Silhouette Score Analysis

Principal Component Analysis (PCA)

3D PCA Visualization

Dendrograms

t‑SNE (optional extension)

The goal is to compare clustering performance and visualize how well the algorithms separate the three Iris species.

📂 Dataset
The project uses the built‑in Iris dataset from sklearn.datasets.

It contains:

Feature	Description
sepal length (cm)	Numeric
sepal width (cm)	Numeric
petal length (cm)	Numeric
petal width (cm)	Numeric
species	0 = setosa, 1 = versicolor, 2 = virginica


🧰 Libraries Used
python
numpy, pandas, matplotlib, seaborn
sklearn.datasets, sklearn.preprocessing
sklearn.cluster, sklearn.decomposition
sklearn.manifold, sklearn.metrics
scipy.cluster.hierarchy
🚀 Workflow Summary
1️⃣ Load & Explore Dataset
Display first rows, shape, statistics, missing values.

Visualize species distribution.

2️⃣ Preprocessing
Drop labels (unsupervised learning).

Standardize features using StandardScaler.

3️⃣ Determine Optimal K
Elbow Method (K = 1–10)

Silhouette Score Analysis (K = 2–10)

4️⃣ K‑Means Clustering
Fit model with K=3.

Evaluate using silhouette score.

Compare cluster labels with actual species.

5️⃣ Hierarchical Clustering
Agglomerative clustering (Ward linkage).

Dendrogram visualization.

Silhouette score comparison.

6️⃣ PCA Visualization
2D PCA scatter plots:

Actual species

K‑Means clusters

Hierarchical clusters

Explained variance ratio.

7️⃣ PCA (Full)
Variance per component.

Cumulative variance plot.

8️⃣ 3D PCA Visualization
3D scatter plot colored by K‑Means clusters.

📊 Key Visualizations
Elbow Curve

Silhouette Score Plot

Dendrogram (Ward Linkage)

2D PCA Cluster Comparison

3D PCA Cluster Visualization

Explained Variance Bar & Line Charts

These plots help interpret cluster separation and dimensionality reduction effectiveness.

🏁 Results Summary
Optimal K ≈ 3 (matches true species count)

K‑Means and Hierarchical clustering both achieve strong silhouette scores.

PCA reveals that two components explain ~95% of variance.

Clusters align closely with actual species, especially setosa which is well‑separated.

📦 How to Run
Clone the repository:

bash
git clone https://github.com/<your-username>/<your-repo>.git
Install dependencies:

bash
pip install -r requirements.txt
Run the notebook:

bash
jupyter notebook Unsupervised_Learning_Iris.ipynb
📝 Notes
This project is ideal for learning clustering fundamentals.

You can extend it with:

DBSCAN

Gaussian Mixture Models

t‑SNE visualization

Feature importance analysis

📧 Contact
If you have questions or want to collaborate, feel free to reach out or open an issue in the repository.

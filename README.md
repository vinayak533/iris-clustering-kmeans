# Iris Dataset Clustering with KMeans

This project applies KMeans clustering to the classic Iris flower dataset to identify natural groupings of iris flowers based on their morphological features.

## 📌 Project Highlights

- Exploratory scatter plots of sepal and petal features.
- Unsupervised clustering using `KMeans`.
- Feature scaling using `preprocessing.scale`.
- Determining optimal number of clusters with the **Elbow Method**.
- Visual comparison of predicted clusters vs actual species.

## 📊 Clustering Process

1. **Data Preprocessing**
   - Loaded data from CSV.
   - Visualized initial feature distribution.

2. **Initial KMeans Clustering (Unscaled)**
   - Applied KMeans with `n_clusters=2`.

3. **Feature Scaling**
   - Scaled data using `sklearn.preprocessing`.

4. **Clustering on Scaled Data**
   - Re-applied KMeans on scaled features.
   - Tested different cluster values (2, 3, 5).

5. **Elbow Method**
   - Plotted Within-Cluster Sum of Squares (WCSS) to find optimal `k`.

6. **Result Comparison**
   - Compared clustering results with actual species labels using color maps.

## 📷 Sample Visualizations

- Sepal Length vs Sepal Width (Clustered)
- Petal Length vs Petal Width (Clustered)
- Elbow Method Plot

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


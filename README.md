# Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using the K-Means clustering algorithm. The dataset includes information about annual income and spending score of mall customers, helping identify different customer groups based on behavior.

---

## Objective

To group customers into meaningful clusters based on their income and spending habits using unsupervised learning.

---

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

- **File:** `Mall_Customers.csv`
- **Features used:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## Workflow Summary

1. Uploaded the dataset
2. Selected relevant features
3. Visualized original data
4. Applied Elbow Method to find optimal K
5. Trained KMeans model
6. Labeled clusters
7. Visualized results with centroids
8. Evaluated clustering using Silhouette Score

---

## Steps Performed

1. **Loaded and cleaned the dataset**
2. **Visualized the raw customer data**
3. **Applied the Elbow Method** to determine the optimal number of clusters
4. **Trained the KMeans algorithm** with the chosen number of clusters
5. **Visualized the clustered data** with color-coded clusters and centroids
6. **Evaluated the clustering performance** using Silhouette Score

---

## Visuals

| File Name                    | Description                                |
|-----------------------------|--------------------------------------------|
| `raw_customer_data.png`     | Raw scatter plot of customer distribution  |
| `elbow_method.png`          | Elbow Method to determine optimal K        |
| `customer_segments_kmeans.png` | Final cluster visualization with centroids |

---

## Output Sample

- Scatter plot showing customer clusters
- Cluster centroids marked with black “X”
- Silhouette Score displayed for cluster validation

---

## Conclusion

K-Means effectively segmented customers into distinct groups based on their income and spending patterns. This can help in targeted marketing, promotions, and strategic business decisions.

# 🧠 Mall Customer Segmentation using K-Means Clustering

This project demonstrates unsupervised learning using the **K-Means clustering algorithm** on the `mall_customers.csv` dataset to segment customers based on spending behavior and income.

---

## 📌 Objective

- Group similar customers using K-Means Clustering
- Analyze patterns among clusters (e.g., high income, low spending)
- Visualize clusters in feature space and PCA-reduced space
- Determine optimal number of clusters using Elbow Method & Silhouette Score

---

## 📂 Dataset

The dataset `mall_customers.csv` contains:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn** for KMeans, PCA, silhouette scoring

---

## 🔍 Key Features

- **Data Preprocessing**: Encoding gender, removing unused columns
- **Cluster Analysis**: Optimal `K` detection using WCSS & silhouette score
- **Visualization**:
  - Cluster scatter plots
  - PCA 2D projection
  - Gender-based analysis
- **Evaluation**:
  - Inertia (WCSS)
  - Silhouette Score

---

## 📈 Results

- Optimal number of clusters: **5**
- Clear segmentation of customer types (e.g., high-income high-spenders)
- PCA-based visualization shows distinct, well-separated groups

---

## ✅ Conclusion

K-Means clustering allowed us to segment mall customers into distinct groups based on spending behavior and income. These insights can be used for targeted marketing and strategic decisions.

---


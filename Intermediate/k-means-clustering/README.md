# 🛍️ K-Means Clustering on Mall Customer Data

This project applies **K-Means Clustering** to segment mall customers based on their **Annual Income** and **Spending Score**. It was developed as part of the **Intermediate Task** for the Codveda Internship Program.

## 📌 Objective

To discover distinct customer segments in mall data using unsupervised machine learning, enabling better customer targeting and strategy building.

## 📁 Dataset

- **Name:** Mall_Customers.csv  
- **Attributes:**
  - `CustomerID`: Unique ID
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🧠 Techniques Used

- K-Means Clustering
- Elbow Method for optimal K
- Feature Scaling using StandardScaler
- Cluster Visualization using Matplotlib

## 📊 Steps Performed

1. **Data Cleaning & Exploration**
   - Checked for missing values
   - Descriptive statistics and data preview

2. **Preprocessing**
   - Removed `CustomerID` and `Gender`
   - Standardized numerical features: `Age`, `Annual Income`, `Spending Score`

3. **Modeling**
   - Ran K-Means for K = 1 to 10
   - Used **Elbow Method** to choose `K=5`

4. **Visualization**
   - Plotted customer clusters in 2D
   - Marked centroids with black `X`

## 📈 Elbow Plot

The elbow plot helps identify the optimal number of clusters by evaluating **inertia** (WCSS - within cluster sum of squares).

## 🎨 Cluster Visualization

Each color represents a unique customer segment:
- High spenders with high income
- Low income, low spending
- Medium income, high spending
- ...etc.

[Cluster Visualization](kmeans_plot.png)


## 🔧 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

## ✅ Results

- 5 distinct clusters identified
- Useful for business to target customer groups
- Centroids clearly define the center of each cluster

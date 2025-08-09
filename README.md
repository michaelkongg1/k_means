# 🛍️ Mall Customer Segmentation – K-Means Clustering

This machine learning project segments mall customers based on demographics and spending behavior using **K-Means clustering**. The analysis helps identify distinct customer groups for targeted marketing, promotions, and retention strategies.

---

## 🛠 Tools Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- **Jupyter Notebook** (`.ipynb`)
- K-Means clustering with **Elbow Method** for optimal `k`

---

Key steps:
- Load and explore dataset (Age, Gender, Annual Income, Spending Score)
- Determine optimal clusters with **Elbow Method**
- Perform **K-Means clustering** and visualize results in 2D/3D
- Profile each cluster to understand customer types

---

## ✅ Insights
- **Cluster 1:** High Income, Low Spending → Affluent but conservative buyers  
- **Cluster 2:** Mid Income, High Spending → Loyal high-value customers  
- **Cluster 3:** Young, Low Income, High Spending → Trend-driven, impulsive buyers  

---

## 📁 Project Structure
```
mall-customer-segmentation/
├── notebooks/
│   └── Mall Clustering Project.ipynb
├── images/
│   ├── elbow_method.png
│   ├── clusters_2d.png
│   └── clusters_3d.png
└── README.md
```

---


## 🚀 Potential Improvements
- Add **customer count** and average metrics per cluster
- Use **PCA** or **t-SNE** for dimensionality reduction
- Export cluster assignments for use in marketing campaigns

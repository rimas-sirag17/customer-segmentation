#  Customer Segmentation using K-Means

##  Project Overview
This project applies **K-Means Clustering** to segment mall customers based on:

- Annual Income (k$)
- Spending Score (1–100)

The goal is to identify distinct customer groups that can help businesses design targeted marketing strategies.

---

##  Dataset
Dataset used: **Mall Customers Dataset (Kaggle)**

Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, we used:
- Annual Income (k$)
- Spending Score (1-100)

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

##  Project Workflow

1. Data Loading
2. Data Exploration
3. Feature Selection
4. Data Scaling (StandardScaler)
5. Elbow Method (Optimal K selection)
6. K-Means Clustering
7. Cluster Visualization (2D Plot)
8. Silhouette Score Evaluation
9. Cluster Analysis (Average Spending per Cluster)

---

##  Results

- Optimal number of clusters: **5**
- Customers were grouped into meaningful segments such as:
  - High income / High spending
  - High income / Low spending
  - Low income / High spending
  - Low income / Low spending
  - Average income / Average spending

These insights can help in targeted marketing and customer personalization strategies.

---

##  Visualization

The clusters are visualized in a 2D scatter plot using:
- X-axis: Annual Income
- Y-axis: Spending Score
- Centroids marked clearly

---

##  Bonus

- Silhouette Score used to evaluate clustering quality
- DBSCAN clustering (optional experimentation)

---

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
Open `customer_segmentation.ipynb` in Jupyter or Googleng Track

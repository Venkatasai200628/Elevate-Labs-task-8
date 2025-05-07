# Elevate-Labs-task-8
# K-Means Clustering - Customer Segmentation

## Objective
This project performs unsupervised learning using **K-Means Clustering** to segment customers based on key features. The goal is to identify meaningful groups in the data to support business strategies such as targeted marketing.

---

## Dataset
The dataset contains customer demographic and behavioral data:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

Source: Mall Customer Segmentation dataset

---

## Techniques Used

- **Data Preprocessing**
  - Dropped `CustomerID`
  - Encoded categorical `Gender`
  - Standardized features using `StandardScaler`

- **Dimensionality Reduction**
  - Used **PCA** to reduce dimensions to 2D for visualization

- **Clustering**
  - Applied **K-Means Clustering**
  - Used the **Elbow Method** to determine the optimal number of clusters
  - Visualized the clusters using **Seaborn**

- **Evaluation**
  - Calculated **Silhouette Score** to evaluate the clustering performance

---

## Results

- Optimal clusters: **5**
- Silhouette Score: *(your score here, e.g., 0.55)*

Clusters were clearly separable in 2D PCA space, confirming the effectiveness of segmentation.

---

## Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Files
- `kmeans_clustering.ipynb` – Main notebook
- `your_dataset.csv` – Dataset used
- `README.md` – Project overview

---

## How to Run

1. Clone this repo.
2. Open the Jupyter Notebook or run it in Google Colab.
3. Install dependencies if missing:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn

<h1 align="center">📊 K-Means Clustering on Mall Customer Data</h1>

<p align="center">
  An interactive and insightful customer segmentation project using K-Means Clustering. Helps understand customer behavior based on spending patterns and demographics.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pandas-1.5+-darkgreen?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-visuals-blue?style=flat-square&logo=seaborn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-interactive-lightblue?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciKit Learn-1.3+-orange?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-2D plots-blueviolet?style=flat-square&logo=matplotlib&logoColor=white"/>
</p>

---

## 📝 Project Overview

This project uses **K-Means Clustering** to group mall customers based on features like age, income, and spending score. The goal is to identify customer segments to support targeted marketing and better business decisions. The dataset contains key demographic and spending information from a mall's customer base.

---

## 🧠 What is K-Means?
K-Means is an iterative algorithm that partitions the dataset into k distinct, non-overlapping clusters.
Each data point belongs to the cluster with the nearest mean (cluster centroid), and the centroids are updated iteratively to minimize the intra-cluster variance.

---

## 📌 Key Features

* 📦 **Data Preprocessing**

  * Null and duplicate check
  * Encoding of categorical column (`Gender`)
  * Outlier analysis via boxplots

* 📊 **Visualization**

  * Histograms, boxplots, and scatter plots using **Seaborn** and **Matplotlib**
  * Interactive clustering result visualized with **Plotly**

* 🤖 **K-Means Clustering**

  * Elbow Method for optimal cluster count
  * Clustering based on numerical features
  * Dimensionality reduction using PCA for 2D visualization

* 📈 **Cluster Evaluation**

  * Silhouette Score
  * Davies-Bouldin Index

---

## 🧪 Dataset Info

* **Name**: `Mall_Customers.csv`
* **Attributes**:

  * `CustomerID`
  * `Genre`
  * `Age`
  * `Annual Income (k$)`
  * `Spending Score (1-100)`

---

## 🧠 Tech Stack

| Technology       | Description                         |
| ---------------- | ----------------------------------- |
| **Python**       | Main programming language           |
| **Pandas**       | Data manipulation and handling      |
| **Seaborn**      | Statistical data visualization      |
| **Matplotlib**   | Custom visual plots                 |
| **Plotly**       | Interactive data visualization      |
| **Scikit-learn** | KMeans, PCA, and evaluation metrics |
| **Scipy**        | Advanced statistical analysis       |

---

## 🔍 How It Works

1. Load and clean the customer dataset.
2. Perform EDA (Exploratory Data Analysis) and visualize feature distributions.
3. Use the Elbow Method to determine the optimal number of clusters.
4. Apply **KMeans clustering** algorithm.
5. Evaluate clusters with silhouette and Davies-Bouldin scores.
6. Reduce dimensions using PCA for visualization.
7. Display results using both static and interactive plots.


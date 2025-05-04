
# 🔥 US Wildfire Clustering with KMeans & PCA

This project applies **Unsupervised Machine Learning** techniques to analyze and cluster wildfire events across the United States using real historical data. The goal is to identify distinct wildfire behavior patterns based on size, duration, and geographical location.

---

## 📌 Project Overview

- **Dataset**: https://www.kaggle.com/code/dilrabonu/us-wildfire
- **Techniques Used**:  
  - KMeans Clustering  
  - PCA for Dimensionality Reduction  
  - Elbow Method for Model Selection  
  - StandardScaler for Feature Normalization
- **Features Used for Clustering**:
  - `FIRE_SIZE` (acres)
  - `Days_to_extinguish_fire`
  - `LATITUDE`, `LONGITUDE`

---

## 🧠 Objective

The main goal of this project is to:
- Cluster wildfire incidents into meaningful groups
- Visualize high-dimensional data in 2D using PCA
- Understand spatial and behavioral patterns of wildfires
- Contribute to wildfire prevention and resource allocation research

This work contributes directly to my **Master’s Thesis**:  
**"AI-Powered Wildfire Detection and Monitoring Using Explainable Deep Learning Models"**

---

## 🔍 Key Insights

| Cluster | Characteristics |
|---------|------------------|
| **0** | 🔘 Mid-sized fires, quickly extinguished |
| **1** | 🟢 Tiny, low-risk fires (controlled rapidly) |
| **2** | 🔴 Large-scale, long-duration fires — major threat regions (Pacific Northwest) |

---

## 📊 Visualizations

- 📌 **PCA Projection of Clusters**  
  Plotted in 2D to observe cluster separation visually.

- 📌 **Elbow Method**  
  Confirmed that **k = 3** was the optimal number of clusters.

- 📌 **Cluster Summary**  
  Showed clear differences in fire size, duration, and region.

---

## 🧰 Tech Stack

- **Language**: Python 3.10
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (KMeans, PCA, StandardScaler)




![image](https://github.com/user-attachments/assets/a7bbfe67-6f07-4ad7-94f7-629cb3dd9cc3)

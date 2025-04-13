# 🔋 Smart Power Management for Battery-Operated Devices using K-Means Clustering

This project optimizes power usage in battery-operated devices by analyzing device behavior using **unsupervised learning**. With the help of **K-Means Clustering**, the system dynamically assigns one of two power modes — **Normal Mode** and **Power-Saving Mode** — based on real usage patterns extracted from smartphone activity data.

> ⚠️ **Disclaimer:** The primary dataset used in this project was sourced from a public repository on [Mendeley Data](https://data.mendeley.com/datasets/bpsrw76hgx/6). I do **not own** or claim any rights to the original dataset. All rights belong to the respective dataset authors.

---

## 🧠 Overview

Modern battery-powered devices need intelligent power control systems to extend battery life without affecting performance. This project proposes a **machine learning-based solution** that classifies power consumption behavior without needing labeled data, using clustering algorithms.

### ✅ Project Highlights

- 📊 K-Means Clustering applied to power usage patterns
- ⚡ Classifies device behavior into two modes:
  - **Cluster 0** → Normal Mode
  - **Cluster 1** → Power-Saving Mode *(or vice versa depending on cluster center values)*
- 📈 Visual analysis through multiple plots
- 🧹 Preprocessing and dimensionality reduction using PCA
- 🧾 Multiple datasets used: original and cleaned versions

---

## 📊 Visualizations Included

- 📌 **Feature Distribution Histogram**
- 🌡️ **Correlation Heatmap**
- 🔟 **Top 10 Principal Features (PCA)**
- 💧 **Elbow Method Plot** – for optimal k
- 📉 **Scree Plot** – variance explained by components
- 🌀 **2D Cluster Visualization** using PCA-transformed features

---

## 🛠️ How it Works

1. **Load and Clean Data**
   - Remove irrelevant features
   - Handle missing values
   - Normalize and scale features

2. **Apply PCA**
   - Reduce dimensions while preserving variance
   - Select top 10 contributing features

3. **Clustering with K-Means**
   - Set `k=2` for binary mode classification
   - Assign clusters to represent power modes

4. **Visualization**
   - Graphical representation of clusters, distributions, and feature importance

---

## 📈 Dataset Info

- **Original Source**: [Smartphone Dataset for Battery Usage - Mendeley Data](https://data.mendeley.com/datasets/bpsrw76hgx/6)
- **Disclaimer**: I do not own this dataset.
- Data includes:
  - CPU usage
  - Battery charge/discharge
  - Screen-on time
  - Application activity
  - Sensor data

---

## 📚 References

- [Smartphone Battery Usage Dataset](https://data.mendeley.com/datasets/bpsrw76hgx/6)
- Scikit-learn Documentation
- PCA & Clustering best practices

---

## Made by Vidhyarth

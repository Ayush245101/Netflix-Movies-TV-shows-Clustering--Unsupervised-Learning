# 🎬 Netflix Movies & TV Shows Clustering  
_Unsupervised Learning Project | Data Science & Machine Learning_

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-ff69b4)

---

## 📌 Overview

This project uses **unsupervised machine learning** to cluster Netflix titles based on key features like genre, type, duration, and release year. The goal is to uncover hidden patterns and group similar content without using predefined labels.

### 🔍 Problem Statement

Netflix has a vast library of movies and TV shows. Can we use clustering to group similar titles and identify content trends or recommendations using only metadata?

---

## 📊 Dataset

- 📂 Source: [Netflix Dataset on GDrive]((https://drive.google.com/file/d/1kyC9xT_VJPTyRf76nBIsLXP1lafTy7f3/view?usp=sharing))
- 🧾 Format: CSV
- 📈 Size: ~8000 records
- 🎯 Features: Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre (listed_in), Type

---

## 🚀 Techniques Used

| Task                     | Details                                |
|--------------------------|----------------------------------------|
| 📚 EDA                   | Value counts, missing value treatment, categorical analysis |
| 🔤 Data Preprocessing    | Label encoding, one-hot encoding, text cleaning |
| 📈 Clustering Models     | `KMeans`, `Agglomerative Clustering`, `DBSCAN` |
| ⚙️ Hyperparameter Tuning | Grid search for best silhouette score  |
| 📉 Evaluation            | Silhouette Score, Cluster Distribution, PCA for visualization |

---

## 🧠 Models and Evaluation

| Model                  | Optimal Params | Silhouette Score |
|------------------------|----------------|------------------|
| KMeans                 | k=4            | 0.45             |
| Agglomerative Clustering | linkage='ward' | 0.43           |
| DBSCAN                 | eps=0.5, min_samples=5 | ~0.31      |

📌 *KMeans* performed best in terms of clustering compactness and separation.

---

## 📁 Folder Structure


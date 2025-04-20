
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/Netflix_icon.svg" width="100" />
  <h1 align="center">Netflix Movies & TV Shows Clustering</h1>
  <p align="center"><em>🔍 Unsupervised Machine Learning Project using Netflix Dataset</em></p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.10-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-ff69b4?style=flat-square" />
</p>

---

## 📌 Overview

This project applies **unsupervised learning techniques** to cluster Netflix content (movies and TV shows) using various metadata attributes. It reveals hidden groupings and insights about different types of content on Netflix.

---

### 🔍 Problem Statement

Netflix has a vast library of movies and TV shows. Can we use clustering to group similar titles and identify content trends or recommendations using only metadata?

---

## 📊 Dataset

- 📂 Data: Netflix Dataset on GitHub (NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv)
- 🧾 Format: CSV
- 📈 Size: ~8000 records
- 🎯 Features: Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre (listed_in), Type

---

## 🔧 Tools & Technologies

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-FB9820?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
</p>

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
| DBSCAN                 | eps=0.3, min_samples=9 | ~0.5      |

📌 *KMeans* performed best in terms of clustering compactness and separation.

---


👀 **Explore the full project on GitHub**:  
[![View Project](https://img.shields.io/badge/View_Project-GitHub-black)](https://github.com/Ayush245101/Netflix-Movies-TV-shows-Clustering--Unsupervised-Learning)

---



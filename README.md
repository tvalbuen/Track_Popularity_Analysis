# 🎵 Track Popularity Analysis: A Machine Learning Approach to Predict Music Success

## 📘 Overview

This project explores the use of machine learning techniques to predict and understand the factors behind the **popularity of music tracks**. Leveraging data-driven methods, we aim to identify the audio features that contribute most significantly to whether a song becomes a hit.

The analysis involves:
- **Data preprocessing** to clean and prepare the dataset
- **Segmentation** using K-Means clustering
- **Regression** to assess feature impact
- **Classification** to predict track popularity status

---

## 🔍 Problem Statement

With the increasing use of streaming platforms, the ability to forecast a song's popularity using audio features has become a valuable asset for producers, marketers, and streaming services. This project tackles the question:

> _"Can we predict how popular a track will be using its musical attributes?"_

---

## 📊 Project Pipeline

### 1. 📦 Dataset Description
- Audio features of music tracks (e.g., energy, danceability, tempo, loudness).
- Target variable: **popularity** score of a song.

### 2. 🧹 Data Preprocessing
- Removal of missing values.
- One-hot encoding for categorical features (e.g., genre).
- Outlier detection and elimination to ensure model robustness.

### 3. 📈 Segmentation Analysis
- **K-Means Clustering** segments songs into clusters with similar musical characteristics.
- Used to identify distinct styles or feature patterns that emerge across tracks.

### 4. 📉 Linear Regression
- Explores the linear relationships between track features and their popularity score.
- Helps interpret the influence of features like energy, acousticness, or speechiness.

### 5. ✅ Logistic Regression
- Converts the popularity prediction into a binary classification:
  - Popular (1)
  - Not popular (0)
- Evaluates performance using accuracy and confusion matrix.

---

## 🧰 Technologies Used

| Technology        | Purpose                             |
|-------------------|-------------------------------------|
| `Python`          | Programming language                |
| `Pandas`, `NumPy` | Data manipulation                   |
| `Matplotlib`, `Seaborn` | Data visualization             |
| `Scikit-learn`    | Machine learning models (clustering, regression, classification) |

---

## 🧠 Insights & Takeaways

- Certain audio features (like danceability and loudness) are strong indicators of popularity.
- Tracks can be segmented into distinct musical clusters, which can help tailor marketing or playlist strategies.
- Logistic regression provides a simplified and interpretable model to predict hits.

---

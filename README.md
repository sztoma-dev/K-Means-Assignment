# K-Means Clustering (Manual Implementation)

This repository contains a **pure Python implementation of K-Means clustering** on a 2D dataset (`data.csv`) without using any external libraries such as NumPy, pandas, or scikit-learn. It is designed for **educational purposes** and to meet **lab restrictions** for practicing algorithm fundamentals.

---

## 🚀 Features

✅ Manual K-Means implementation using:

* **Random centroid initialization**
* **Euclidean distance calculation**
* **Centroid update using mean calculations**

✅ Uses **minimum number of loops** with list comprehensions to maintain clarity while reducing nested iterations.

✅ Supports **multiple `k` values** for experimentation:

* `k = 3, 4, 5, 6, 7`

✅ **Runs cleanly on Google Colab** without requiring any package installations.

✅ Prints clear cluster and centroid outputs for your **lab reports**.

---

## 📂 Files

* `data.csv` – Input dataset (2D points for clustering)
* `kmeans_manual.py` – Contains the manual K-Means implementation (ready to paste into Google Colab)

---

## ⚡ How to Run

1️⃣ Upload `data.csv` to your Google Colab environment.

2️⃣ Paste the code from `kmeans_manual.py` into a Colab cell.

3️⃣ Run the cell to view:

* Cluster assignments
* Centroid coordinates for each `k`

---

## 🛠️ Core Concepts Practiced

✅ Understanding the **K-Means algorithm without black-box libraries**
✅ Calculating Euclidean distances manually
✅ Using Python’s built-in `csv`, `math`, and `random` libraries
✅ Managing convergence using manual centroid comparison
✅ Preparing for viva and lab understanding

---

## 🧪 Future Enhancements (optional learning practice)

* Add Elbow Method (manual WCSS calculation) to find the optimal `k`.
* ASCII plotting or basic text-based cluster visualization.
* Refactor to use optional `matplotlib` for visual outputs if allowed.

---

## 📜 License

This project is **free for educational use** and practice in your Data Mining, AI Lab, and Machine Learning coursework.

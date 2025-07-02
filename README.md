# K-Means Clustering (Manual Implementation with Visualization)

This repository contains a **manual K-Means clustering implementation using `numpy` for data handling** and **`matplotlib` for visualization**, fulfilling all **lab assignment requirements** for your **Data Mining / Machine Learning course**.

---

## 🚀 Features

✅ **Loads data directly** from a GitHub raw CSV link using `numpy`.
✅ **Manual implementation** of the K-Means algorithm (no scikit-learn or built-in clustering).
✅ Uses **minimal loops**, leveraging `numpy` for efficient distance and mean calculations.
✅ **Visualizes the resulting clusters with different colors and clear centroids** for each $k$.
✅ **Plots for $k = 3, 4, 5, 6, 7$** to analyze clustering visually.
✅ **Google Colab–ready with no path changes required.**

---

## 📂 Files

* `data.csv` – Dataset of 2D points for clustering (automatically loaded from URL).
* `kmeans_manual_visual.py` – Contains the clean, ready-to-paste Google Colab code with:

  * Data loading using `numpy`
  * Manual K-Means implementation
  * Cluster visualization using `matplotlib`

---

## ⚡ How to Run

1️⃣ Open **Google Colab**.
2️⃣ Copy and paste the code from `kmeans_manual_visual.py`.
3️⃣ Run the cell to:

* Load the dataset automatically.
* Perform K-Means clustering for each $k = 3, 4, 5, 6, 7$.
* View **scatter plots** with:

  * Different colors for each cluster
  * Centroids marked with **black '×'**

---

## 🛠️ Concepts Covered

✅ Understanding **K-Means from scratch** without library black boxes.
✅ Calculating **Euclidean distances and centroids manually using `numpy`**.
✅ Practicing **visual analysis of clusters** to evaluate the effectiveness of different `k`.
✅ Preparation for **lab notebook reports and viva**.

---

## 🖼️ Example Output

* **Colored scatter plots** with cluster separation.
* Centroids clearly marked to show convergence.
* Easy to compare clustering structures as `k` changes.

---

## 🧪 Future Enhancements (Optional Practice)

* Add Elbow Method using **manual WCSS calculation** to determine optimal `k`.
* Cluster quality evaluation using silhouette scores (if required).
* Save plots automatically for direct inclusion in your lab reports.

---

## 📜 License

This project is **free for educational use** in your Machine Learning and Data Mining coursework.

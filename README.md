# Machine Learning Algorithms & Color Image Segmentation

This repository contains practical implementations of foundational Machine Learning and Computer Vision algorithms built using Python, Scikit-Learn, OpenCV, and Matplotlib in Google Colab.

---

## 📌 Features & Implementations
- **K-Nearest Neighbors (K-NN):** Supervised classification on 2D numerical data using `KNeighborsClassifier`.
- **K-Means Clustering:** Unsupervised clustering on 2D feature vectors with dynamic centroid visualizations and cluster-wise legends.
- **Color Image Segmentation:** Iterative K-Means clustering ($K=20$) applied on RGB image pixels using OpenCV to segment distinct color regions.

---

## 📁 Repository Structure
- `AI_course.ipynb` : Main Jupyter Notebook containing code implementation, visual outputs, and execution results.
- `knn_kmeans_dataset.csv` : Generated dataset containing 2D numerical features (X,Y) and target class labels.
- `images.jpg` : Sample input image used for testing OpenCV color segmentation.

---

## 🛠️ Required Libraries
To run the project locally or in Google Colab, ensure you have the following libraries installed:

```bash
pip install opencv-python numpy scikit-learn matplotlib pandas
How to Run
Open Google Colab.

Upload AI_course.ipynb to Google Colab.

Ensure knn_kmeans_dataset.csv and images.jpg are uploaded to the session storage.

Run all notebook cells sequentially.

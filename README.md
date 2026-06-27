# Assignment 9: Unsupervised Learning

## Project Overview

This project demonstrates the use of **unsupervised learning** techniques on the **Wine dataset** from scikit-learn. The objective is to group similar wine samples based on their chemical properties without using target labels.

The project includes:

* Data preprocessing
* K-Means Clustering
* Hierarchical Clustering
* Principal Component Analysis (PCA)
* Model evaluation using the Silhouette Score
* Deployment and monitoring strategies

## Dataset

Dataset: Wine Dataset
Source: scikit-learn (load_wine())

The dataset contains several chemical features of different wine samples and is commonly used for clustering and dimensionality reduction tasks.

## Files in this Repository

* `Assignment9_UnsupervisedLearning.ipynb` – Google Colab notebook containing the complete implementation.
* `Report_Assignment9.pdf` – Summary report of the project.
* `README.md` – Project overview and instructions.

## Required Libraries

The project requires the following Python libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn

## How to Run the Notebook

1. Download or clone this GitHub repository.
2. Open `Assignment9_UnsupervisedLearning.ipynb` using **Google Colab** or **Jupyter Notebook**.
3. Install the required libraries if they are not already installed.
4. Run all notebook cells from top to bottom.
5. The notebook will perform data preprocessing, clustering, PCA visualization, model evaluation, and display the final results.

## Results

* The Elbow Method suggested 3 as the optimal number of clusters.
* Both K-Means and Hierarchical Clustering were successfully implemented.
* PCA reduced the dataset to two dimensions for clear visualization.
* K-Means achieved a slightly higher Silhouette Score, indicating better clustering performance than Hierarchical Clustering.



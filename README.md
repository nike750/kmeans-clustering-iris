# 🌸 K-Means Clustering on Iris Dataset

## 📌 Project Overview

This project demonstrates the application of **K-Means Clustering**, an unsupervised machine learning algorithm, to group data points based on their similarity. The model is applied to the **Iris dataset**, which contains measurements of different flower species.

The goal of this project is to identify natural groupings in the dataset without using predefined labels and to understand how clustering algorithms can reveal hidden patterns in data.

---

## 🎯 Objectives

* Perform **data exploration and preprocessing**
* Apply **feature scaling** for distance-based learning
* Determine the optimal number of clusters using the **Elbow Method**
* Implement **K-Means clustering**
* Visualize clusters and interpret the results

---

## 📂 Dataset Description

The dataset used is the **Iris dataset**, which contains 150 observations and 5 columns:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species (categorical – removed for clustering)

Since K-Means works only with numerical data, the `species` column was excluded during preprocessing.

---

## ⚙️ Methodology

### 1. Data Exploration

Initial analysis was performed to understand the structure of the dataset, check for missing values, and review statistical summaries.

### 2. Data Preprocessing

* Removed categorical column (`species`)
* Ensured dataset contained only numerical features
* Verified no missing values

### 3. Feature Scaling

Standardization was applied using **StandardScaler** to ensure all features contribute equally to distance calculations.

### 4. Finding Optimal Clusters

The **Elbow Method** was used to determine the optimal number of clusters by plotting Within-Cluster Sum of Squares (WCSS).
The optimal number of clusters was found to be **K = 3**.

### 5. Model Implementation

The **K-Means algorithm** was applied with 3 clusters to group similar data points.

### 6. Visualization

Clusters were visualized using scatter plots, where each point represents a data instance and colors indicate cluster membership.

---

## 📊 Results and Interpretation

The algorithm successfully grouped the dataset into three distinct clusters. Analysis of cluster means revealed:

* One cluster represents flowers with **smaller petal and sepal measurements**
* Another cluster represents flowers with **larger feature values**
* The third cluster represents **intermediate-sized flowers**

These clusters closely align with the natural grouping of iris flower species, demonstrating the effectiveness of K-Means clustering.

---

## 🛠️ Tools and Technologies Used

* Python
* pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📈 Key Learnings

* Importance of **data preprocessing and scaling**
* Understanding how **distance-based algorithms** work
* Practical use of the **Elbow Method**
* Interpreting clustering results beyond just visualization

---

## 🚀 Future Improvements

* Apply **PCA (Principal Component Analysis)** for better visualization
* Compare K-Means with other clustering algorithms (e.g., DBSCAN, Hierarchical Clustering)
* Test the model on larger and more complex datasets

---

## 👨‍💻 Author

nike750

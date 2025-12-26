📊 PCA for Visualization and Dimensionality Reduction
📌 Project Overview

This project demonstrates how Principal Component Analysis (PCA) is used for:

Visualizing high-dimensional data in 2D

Reducing dimensions to speed up machine learning models

Two datasets are used:

Iris Dataset → PCA for visualization

MNIST Dataset → PCA for dimensionality reduction + Logistic Regression

🎯 Objectives

Understand how PCA works

Reduce high-dimensional data into fewer components

Visualize data in 2D using PCA

Improve machine learning performance using PCA

🧠 What is PCA?

Principal Component Analysis (PCA) is a dimensionality reduction technique that:

Converts original features into new uncorrelated features

Retains maximum variance (information)

Reduces computational complexity

Helps in visualization and faster model training

🗂️ Dataset Details
1️⃣ Iris Dataset

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Target Classes:

Setosa

Versicolor

Virginica

2️⃣ MNIST Dataset

Handwritten digit images

Each image has 784 features (28×28 pixels)

Target: Digits from 0 to 9

⚙️ Project Workflow
🔹 Part 1: PCA for Visualization (Iris Dataset)

Steps:

Load the Iris dataset

Separate features and target labels

Standardize the feature values

Apply PCA with 2 components

Visualize the data in a 2D scatter plot

Observe how different classes are separated

Result:

PCA reduces 4 features → 2 principal components

Classes become visually distinguishable

Variance retained is displayed using explained_variance_ratio_

🔹 Part 2: PCA for Speeding Up ML (MNIST Dataset)

Steps:

Load the MNIST dataset

Split data into training and testing sets

Standardize the data

Apply PCA keeping 95% variance

Reduce features from 784 → fewer components

Train Logistic Regression on PCA-transformed data

Evaluate model accuracy

Result:

Significant reduction in dimensionality

Faster training time

Good classification accuracy

📈 Why PCA is Important?

Handles high-dimensional data efficiently

Removes redundant features

Improves model performance

Essential for large datasets like images and sensor data

🛠️ Algorithms Used

Principal Component Analysis (PCA)

Logistic Regression

📊 Libraries Used

Python

Pandas

Matplotlib

Scikit-learn

✅ Conclusion

This project shows that PCA is a powerful preprocessing technique that:

Helps visualize complex datasets

Reduces dimensions without major loss of information

Improves speed and efficiency of machine learning models

👩‍💻 Author

Ishwarya R
Artificial Intelligence & Data Science

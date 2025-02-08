# Assignment5PredictiveA
# Clustering Analysis using PyCaret

# Overview

This project performs a comparative performance study of different clustering algorithms using various preprocessing techniques and cluster numbers. The analysis is conducted on a small dataset from the UCI library using PyCaret in Google Colab.

# Dataset

Source: UCI Machine Learning Repository

Dataset Used: Iris dataset (excluding class labels for unsupervised clustering)

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

# Clustering Algorithms Used

K-Means

Affinity Propagation (AP)

Mean Shift

Hierarchical Clustering (HClust)

# Preprocessing Techniques Applied

No Scaling

Standard Scaling (StandardScaler)

Min-Max Scaling (MinMaxScaler)

# Evaluation Process

The dataset is preprocessed using different scaling techniques.

Each clustering algorithm is run with varying numbers of clusters (3, 4, and 5).

The results are collected and saved for further analysis.

# Installation & Setup

To run this project, install PyCaret using the following command:

pip install pycaret

Running the Script in Google Colab

Upload the Python script (clustering_analysis.py) to Google Colab.

Run the script to perform clustering analysis.

The results will be saved as clustering_results.csv.

# Output

The script prints evaluation metrics for each clustering approach.

A CSV file (clustering_results.csv) containing the results is generated.

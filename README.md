# PCA implementation for face dataset

This is a Jupyter Notebook that implements PCA for face recognition using the [Olivetti Faces dataset](https://scikit-learn.org/0.19/datasets/olivetti_faces.html) provided by scikit-learn's `fetch_olivetti_faces` function. The notebook demonstrates how to use the PCA algorithm to reduce the dimensionality of the dataset and visualize the results.

## Dataset

The dataset used in this notebook is from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones). It consists of 561 features extracted from accelerometer and gyroscope signals of 30 volunteers performing six activities: walking, walking upstairs, walking downstairs, sitting, standing, and laying.

## PCA

PCA is a dimensionality reduction technique that transforms a set of correlated features into a set of uncorrelated components that capture most of the variance in the data. PCA can be used to reduce noise, visualize data, and improve performance of machine learning models.

## Notebook

The notebook contains the following steps:

- Loading and exploring the dataset
- Applying PCA to reduce the number of features from (400, 4096) to 2d plane
- Visualizing the 2D projection of the data with different colors for each activity
- Evaluating the explained variance ratio of PCA

## Resources
- [Olivetti Faces dataset](https://scikit-learn.org/0.19/datasets/olivetti_faces.html)

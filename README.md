# Iris-Flower-Classification
# Iris Flower Classification 🌸

This is a machine learning project that classifies iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — using features like sepal length, sepal width, petal length, and petal width.

## 📁 Project Overview

- Dataset: [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Algorithms used:
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier

## 📊 Features

- Visualizes the dataset using `seaborn`
- Trains models using `scikit-learn`
- Evaluates accuracy on test data

## 🧠 Technologies

- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## 📈 Model Training Sample Code

```python
from sklearn.neighbors import KNeighborsClassifier
knn = KNeighborsClassifier(n_neighbors=3)
knn.fit(X_train, y_train)

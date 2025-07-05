# Iris Dataset: EDA, Clustering, Classification & Regression

## Objective

This project demonstrates a full data science workflow using the classic **Iris flower dataset**, covering:

- Exploratory Data Analysis (EDA)
- Clustering with KMeans
- Classification with Logistic Regression & Random Forest
- Regression to predict petal width

The goal is to explore the data, identify patterns, and build predictive models.

---

## Dataset Overview

- **Source**: `sklearn.datasets.load_iris()`
- **Samples**: 150
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target classes**:
  - Setosa
  - Versicolor
  - Virginica

---

## Project Steps

### 1. Exploratory Data Analysis (EDA)
- Summary statistics
- Pairplots
- Correlation heatmaps
- Class distribution

### 2. Clustering
- Applied KMeans (unsupervised learning)
- Elbow method for cluster tuning
- PCA for 2D visualization of clusters

### 3. Classification
- Train/test split
- Logistic Regression and Random Forest
- Evaluation using accuracy, F1-score, and confusion matrix

### 4. Regression
- Predicted petal width using linear regression
- Evaluation using R² and MSE
- Scatter plot of actual vs. predicted values

---

## Tools & Libraries
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Install necessary packages (Colab has most pre-installed)
3. Run the cells step by step

---

## File Structure

iris-ml-project/
├── Iris.ipynb
├── README.md
├── requirements.txt
└── .gitignore

---

## Results Summary

- Best classification accuracy: ~100% with Random Forest
- KMeans formed 3 distinguishable clusters
- Regression model performed well for petal width

---

## Future Improvements
- Try other clustering methods like DBSCAN or Agglomerative Clustering
- Tune hyperparameters using GridSearchCV
- Explore feature selection techniques

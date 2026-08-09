# Decision Tree

This folder contains implementations of Decision Tree algorithms for both classification and regression tasks using Python and machine learning libraries.

## 📌 Overview

Decision Trees are supervised learning algorithms that make predictions by recursively splitting the data based on feature values.

A Decision Tree can be used for both:

- **Classification** – predicting categorical outcomes
- **Regression** – predicting continuous numerical values

The notebooks in this folder demonstrate both applications.

## 📂 Contents

### 1. Decision Tree Classification

**File:** `Decision_tree_cls.ipynb`

This notebook demonstrates the use of a Decision Tree for a classification problem.

The model learns decision rules from the training data and uses them to assign observations to different classes.

### 2. Decision Tree Regression

**File:** `decisiontree_regressor.ipynb`

This notebook demonstrates the use of a Decision Tree for a regression problem.

The model learns relationships between input features and a continuous target variable to make numerical predictions.

## 🌳 How Decision Trees Work

A Decision Tree starts with the complete dataset at the root and recursively divides the data into smaller subsets.

The general process is:

**Dataset → Select Best Split → Create Branches → Repeat Splitting → Leaf Node → Prediction**

For classification, the tree aims to create groups containing similar classes.

For regression, the tree aims to create groups with similar target values.

## 🧠 Concepts Covered

The notebooks cover the practical implementation of:

- Decision Tree Classification
- Decision Tree Regression
- Training and testing a Decision Tree model
- Making predictions
- Evaluating model performance
- Understanding tree-based decision making

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📁 Files

| File | Description |
|---|---|
| `Decision_tree_cls.ipynb` | Decision Tree classification implementation |
| `decisiontree_regressor.ipynb` | Decision Tree regression implementation |

## 🎯 Learning Objective

The purpose of these implementations is to understand how Decision Tree models can be applied to both classification and regression problems as part of supervised machine learning.

---

**Part of the `supervised-ml-implementation` repository.**

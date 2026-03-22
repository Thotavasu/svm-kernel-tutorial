# Support Vector Machine Kernel Analysis

## Overview
This project demonstrates how different kernel functions in Support Vector Machines (SVMs) influence classification performance. The tutorial compares linear, polynomial, and radial basis function (RBF) kernels using both real-world and synthetic datasets.

## Objectives
- Understand how SVM works
- Compare kernel functions
- Analyse model performance
- Visualise decision boundaries

## Dataset
- Heart Disease Dataset (included in /data)
- Synthetic Moons Dataset (generated in notebook)

## Methodology
- Data preprocessing and scaling
- Model training using different kernels
- Hyperparameter tuning using GridSearchCV
- Evaluation using accuracy and confusion matrix
- Visualisation of decision boundaries

## Results
The RBF kernel demonstrated superior performance for non-linear data, while the linear kernel struggled with complex patterns.

## How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt

## Support Vector Machine (SVM) for Breast Cancer Classification
## Project Overview:
This project aims to classify breast tumors as malignant (cancerous) or benign (non-cancerous) using a Support Vector Machine (SVM) classifier. It uses the Breast Cancer Wisconsin Diagnostic Dataset, a well-known dataset from the UCI Machine Learning Repository, available through Scikit-learn.

## Key Concepts:
- Hyperplane: A decision boundary that separates classes in feature space.
- Support Vectors: Data points that are closest to the hyperplane and influence its position.
- Margin: The distance between the hyperplane and the nearest support vectors. SVM maximizes this margin.
- Kernel Trick: A method to transform input data into higher-dimensional space to make it linearly separable.

## Dataset Used
- Dataset: Breast Cancer Wisconsin (Diagnostic)
- Source: Scikit-learn’s built-in datasets
- Samples: 569
- Features: 30 numeric features related to cell nuclei measurements
- Target Labels:
0: Malignant
1: Benign

## Problem Type
Binary Classification problem
- Goal: Predict whether a tumor is malignant (0) or benign (1) based on measured features.

## Why Use SVM?
- Linear Kernel: Best for linearly separable data
- RBF Kernel: Best for non-linear relationships

## Evaluation Metrics
To evaluate the model, we use:
- Accuracy Score: Proportion of correctly classified samples.
- Classification Report: Precision, Recall, and F1-Score for both classes.
- Confusion Matrix: A matrix showing actual vs predicted classifications.

## Visualizations
- Confusion Matrix: Helps to visualize true/false positives and negatives.
- Decision Boundary Plot: Shows how the SVM separates two classes in 2D using selected features.

## Summary
- SVM is a robust algorithm for classification, especially when data is high-dimensional.
- Using the Breast Cancer dataset, the SVM performed with high accuracy.
- Both Linear and RBF kernels were compared:
- Linear SVM is simple and fast.
- RBF SVM is more flexible for complex boundaries.

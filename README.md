# Breast Cancer Classification: SVM vs. Decision Tree

## Short Description

This project uses the Wisconsin Breast Cancer dataset (available in scikit-learn) to classify tumors as malignant or benign. It trains and compares the performance of a Support Vector Machine (SVM) and a Decision Tree classifier.

## Project Overview

The notebook `day7/breast_cancer_classification_comparison.ipynb` (originally `Untitled0 (1).ipynb`) performs the following:

1.  **Load Data:** Loads the breast cancer dataset using `sklearn.datasets.load_breast_cancer`.
2.  **Train-Test Split:** Splits the features and target labels into training and testing sets.
3.  **SVM Model:**
    *   Trains an `svm.SVC` model with a linear kernel.
    *   Predicts labels on the test set.
    *   Calculates and prints the confusion matrix and accuracy score.
4.  **Decision Tree Model:**
    *   Trains a `tree.DecisionTreeClassifier` using the 'entropy' criterion.
    *   Visualizes the trained decision tree using `tree.plot_tree`.
    *   Predicts labels on the test set.
    *   Calculates and prints the accuracy score.

## Dataset

*   **Wisconsin Breast Cancer Dataset:** A standard dataset included in scikit-learn, containing features computed from digitized images of fine needle aspirates (FNA) of breast masses. (Data is loaded automatically).

## Models Compared

*   Support Vector Machine (`SVC` with linear kernel)
*   Decision Tree (`DecisionTreeClassifier` with entropy criterion)

## Requirements

*   Python 3
*   Scikit-learn
*   Matplotlib
*   Seaborn (implicitly used for plotting aesthetics, though not directly called)

## How to Run

1.  Ensure you have the required libraries installed (`pip install scikit-learn matplotlib seaborn`).
2.  Run the Jupyter Notebook `day7/breast_cancer_classification_comparison.ipynb`. The dataset will be loaded automatically.

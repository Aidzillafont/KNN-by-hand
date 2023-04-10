# KNN-by-hand
## k-NN and Weighted k-NN Classifier

This project demonstrates the implementation and evaluation of k-Nearest Neighbors (k-NN) and Weighted k-NN classifiers. The goal is to classify data points from a test set using the closest training points from a given training set.

## Getting Started

These instructions will guide you through the process of implementing, evaluating, and comparing the k-NN and Weighted k-NN classifiers.

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn

## Implementation Steps

1. **k-NN Classifier**
    - Calculate the Euclidean distance between each test point and all training points.
    - Select the k points with the smallest distance to the test point.
    - Determine the most common class among the k points.

2. **Weighted k-NN Classifier**
    - Similar to k-NN, but weights the contribution of each neighbor based on their distance.
    - Calculate the Euclidean distance between each test point and all training points.
    - Assign a weight to each distance (e.g., using the inverse of the distance).
    - Determine the class with the highest weighted vote among the k points.

3. **Evaluation**
    - Compute the accuracy for both classifiers.
    - Plot the confusion matrix for each classifier and interpret the results.

## Results

The results section should include a comparison of the normal k-NN and Weighted k-NN classifiers, their accuracy, and a brief interpretation of the confusion matrices.

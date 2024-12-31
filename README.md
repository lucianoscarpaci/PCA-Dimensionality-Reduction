# PCA-Dimensionality-Reduction
## Overview
This project demonstrates PCA dimensionality reduction techniques and applies various classifiers on the Colon Cancer dataset. It includes two Jupyter notebooks with detailed analysis and results.

## Project Structure
- PCA-Classification.ipynb: Classification using KNN, Naive Bayes, Bayes, SVM, and LDA. Plotting of Accuracy VS. Number of Components. Plotting of Kmeans Clustering and Expectation Maximization of the features.

- PCA-Dimension-Reduction.ipynb: Dimensionality reduction using PCA and KPCA using RBF, Poly, and Linear Kernels. Plotting of Kmeans and Expectation Maximization clustering of Projected Compoents.

## Results
PCA-Classification.ipynb:
Before clustering the features using Kmeans and Expectation Maximization, the accuracy of the classifiers were as follows:
SVM classifier accuracy: 35%
KNN classifier accuracy: 34%
Naive Bayes classifier accuracy: 31%
LDA classifier accuracy: 32%
Bayes classifier accuracy: 4%


After clustering the features using Kmeans and Expectation Maximization, the accuracy of the classifiers were as follows:
SVM classifier accuracy: 100%
KNN classifier accuracy: 100%
Naive Bayes classifier accuracy: 90.43%
LDA classifier accuracy: 91.49%
Bayes classifier accuracy: 4.26%

PCA-Dimension-Reduction.ipynb:
The cumulative variance was at 81.55% for 3 Principle Components.
PCA KPCA reduction was tested on the optimal 443 of components at 100% accuracy.
KPCA with train and test projected data had results with Linear kernel: 14.89%
Poly and Combined kernel: 20.21% Highest was Top-Ten Features: 32.98% accuracy.
## Installation
To get started, clone the repository and install the required dependencies:

In Docker and JupyterLab

```bash
git clone https://github.com/lucianoscarpaci/PCA-Dimensionality-Reduction.git
```

## License
This project is licensed under the MIT License.

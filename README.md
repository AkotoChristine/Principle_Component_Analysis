# Principle_Component_Analysis
This Python script demonstrates how to perform Principal Component Analysis (PCA) on a simple dataset. PCA is a dimensionality reduction technique that transforms data into a set of orthogonal components, ordered by the variance they capture from the data.

## Description
The script follows these steps:

Compute Covariance Matrix: The covariance matrix is calculated to understand the relationship between different features in the dataset.
Eigendecomposition: The script performs eigendecomposition on the covariance matrix to get the eigenvalues and eigenvectors.

Sort Eigenvalues and Eigenvectors: Eigenvalues and their corresponding eigenvectors are sorted in descending order of importance.

Select Principal Components: The top k principal components are selected based on the sorted eigenvalues.

Project Data: The original data is projected onto the selected principal components.

### Requirements

Python 3.x
NumPy: For numerical operations and matrix manipulation.
You can install NumPy using pip:

pip install numpy
How to Run
Clone or download the script.
Run the script in your Python environment:
bash

Example Output
The output displays the transformed data in the principal component space, where each row is the original data projected onto the first principal component.

Projected Data:
 [[ 2.12132034]
 [ 3.12132034]
 [ 4.12132034]
 [ 5.12132034]]


# Finding Eigenvalues of a Matrix (PART TWO)

Introduction

This document provides a summary of how to determine the second and third eigenvalues of a given 3x3 matrix using factorization.

Process Summary

To find the eigenvalues, we compute the characteristic equation of the matrix and solve it by factoring and applying the quadratic formula. The first eigenvalue is identified through the Rational Root Theorem, and the remaining two eigenvalues are determined through further algebraic manipulation.

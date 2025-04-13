# Kernel PCA + Support Vector Regression (SVR)

This notebook explores a pipeline combining nonlinear dimensionality reduction with regression:

- **Kernel Principal Component Analysis (KPCA)**: Reduces the dimensionality of the input space using kernel functions (RBF kernel in this case), allowing for nonlinear structure discovery.
- **Support Vector Regression (SVR)**: A robust regression model based on Support Vector Machines, suitable for high-dimensional and transformed feature spaces.

## Objectives

- Visualize and understand the effect of KPCA on synthetic datasets.
- Train SVR models on reduced data and evaluate predictive performance.
- Tune the number of KPCA components and SVR hyperparameters to minimize generalization error.
- Analyze the effect of noise and model complexity.

## File

- `KPCA_SVR_Lab.ipynb`: Jupyter notebook containing data generation, preprocessing, modeling, and evaluation steps.

## Requirements

All dependencies are listed in the root `requirements.txt` of the repository.

## Notes

This work was part of a lab focused on the combination of preprocessing and regression techniques, particularly in nonlinear settings.

# Linear Regression Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org/) 
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)

This folder contains a gradient descent walkthrough for simple linear regression. It blends closed-form intuition with iterative optimization so you can compare the ordinary least squares (OLS) solution against hand-crafted gradient updates.

## Notebook
- `Gradient-descent-step-by-step.ipynb`: Builds a synthetic regression dataset, derives the gradient equations, updates intercept and slope iteratively, and visualizes how each epoch moves the fitted line toward the OLS baseline.

## What You Will Learn
- How to compute mean squared error gradients with respect to slope and intercept.
- Strategies for tuning learning rate and iteration counts to reach convergence.
- How gradient descent and OLS relate when modelling a single feature.

## Suggested Experiments
- Change the learning rate and watch the line oscillate or converge faster.
- Inject additional noise or outliers into the dataset to observe stability.
- Extend the notebook to support batch, mini-batch, or stochastic gradient descent variants.

Additional linear regression variations—regularization, multi-feature support, and polynomial regression—will be added here in future updates.

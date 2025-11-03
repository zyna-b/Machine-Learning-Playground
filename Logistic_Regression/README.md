# Logistic Regression & Perceptron Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)

This folder explores gradient-driven binary classification with logistic regression and perceptron variants. The notebooks emphasise decision boundary intuition, probability calibration, and parity with scikit-learn implementations.

## Notebooks
- `Gradient_Descent_Logistic_Regression.ipynb`: Implements logistic regression from scratch, compares convergence against scikit-learn's solver, and visualises loss curves and class separation.
- `Logistic-Regression-Perceptron-trick-sigmoid.ipynb`: Contrasts a step-activation perceptron, a sigmoid perceptron, and the logistic regression baseline on an aligned synthetic dataset.

## Key Takeaways
- Understand how the logistic cost function and its gradients drive weight updates.
- Compare hard and soft decision boundaries to see when each classifier excels.
- Evaluate convergence visually through probability contours and decision lines.

## Experiment Ideas
- Adjust class imbalance and decision boundary overlap to stress-test convergence.
- Introduce regularisation or momentum to improve stability on noisy data.
- Extend the perceptron notebook to multi-class or one-vs-rest configurations.

Future additions will cover softmax regression, multi-class extensions, and probability calibration techniques to round out the classification toolkit.

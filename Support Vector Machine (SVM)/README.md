# Support Vector Machine (SVM) Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![pandas](https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)

Master the intuition behind Support Vector Machines (SVM) for robust classification. This module visualises hyperplanes, margins, and the kernel trick to demystify how SVMs handle linear and non-linear data.

## Notebook
- `Support_Vector_Machines_(SVM).ipynb` – implements SVM classifiers using scikit-learn, visualises decision boundaries, and explores the impact of kernels and regularization parameters.

## Highlights
- Visualise the "street" (margin) and support vectors that define the optimal hyperplane.
- Compare Linear, Polynomial, and RBF (Radial Basis Function) kernels on complex datasets.
- Understand the bias-variance trade-off by tuning `C` (regularization) and `gamma` (kernel coefficient).

## Requirements
- Python 3.9+
- Packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
```powershell
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook "Support_Vector_Machines_(SVM).ipynb"
```
Run the notebook cells to load the dataset, train the SVM models, and generate the decision boundary plots.

## Experiment Ideas
- Test the SVM on a dataset with high class overlap and observe how the soft margin (`C`) behaves.
- Use a custom kernel function to separate concentric circles or other non-linear patterns.
- Compare SVM performance against Logistic Regression on the same dataset to see where margins matter.

## SEO Keywords
`support vector machine tutorial`, `svm python notebook`, `kernel trick visualization`, `scikit-learn svm example`, `hyperplane classification`, `rbf kernel intuition`

# K-Nearest Neighbours Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![pandas](https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)

Investigate instance-based learning with the Titanic survival dataset. This notebook demonstrates data cleaning, feature engineering, and KNN hyperparameter tuning to balance accuracy and interpretability.

## Notebook
- `KNN_on_Titanic_Dataset (1).ipynb` – prepares the Titanic dataset, performs exploratory analysis, and trains a KNN classifier while validating with cross-validation and confusion matrices.

## Highlights
- Build a preprocessing pipeline: handle missing values, encode categories, and scale numeric features.
- Evaluate the impact of neighbour count, distance metrics, and weighting schemes on model performance.
- Visualise decision boundaries, ROC curves, and feature influence for a well-known benchmark dataset.

## Requirements
- Python 3.9+
- Packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
```powershell
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook "KNN_on_Titanic_Dataset (1).ipynb"
```
Execute cells in sequence to reproduce the data preparation workflow and classifier evaluation.

## Experiment Ideas
- Compare standardisation techniques (min-max vs. z-score) and observe how they alter KNN accuracy.
- Integrate feature selection or dimensionality reduction before training the classifier.
- Swap out KNN for other distance-based models (radius neighbours, nearest centroid) to contextualise results.

## SEO Keywords
`k nearest neighbors titanic`, `knn classification notebook`, `titanic dataset machine learning`, `distance based learning python`, `scikit-learn knn tutorial`

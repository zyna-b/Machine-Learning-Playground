# Ensemble Learning Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4C9A2A?logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

Experiment with bagging and voting ensembles to improve model stability and accuracy. These notebooks show how combining weak learners can outperform a single estimator on noisy datasets.

## Notebooks
- `Bagging.ipynb` – walks through bootstrap aggregation with decision trees, compares bias-variance trade-offs, and visualises prediction intervals.
- `Voting_Ensemble.ipynb` – blends heterogeneous classifiers using hard and soft voting, featuring ROC curves and confusion matrices for evaluation.

## Highlights
- Understand when bagging reduces variance versus when it overfits.
- Benchmark multiple base learners and observe how voting strategies influence performance.
- Learn to tune ensemble hyperparameters such as number of estimators, sampling fractions, and weighting schemes.

## Requirements
- Python 3.9+
- Packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
```powershell
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook Bagging.ipynb
jupyter notebook Voting_Ensemble.ipynb
```
Run each notebook from top to bottom to reproduce the ensemble comparisons and charts.

## Further Experiments
- Replace the default dataset with a real-world classification problem and track the ensemble gains.
- Swap in alternative base estimators (e.g., KNN, SVM) to see how diversity affects voting outcomes.
- Add out-of-bag evaluation for bagging to measure generalisation without a separate validation set.

## SEO Keywords
`ensemble learning tutorial`, `bagging classifier notebook`, `voting ensemble scikit-learn`, `bootstrap aggregation python`, `machine learning ensemble examples`

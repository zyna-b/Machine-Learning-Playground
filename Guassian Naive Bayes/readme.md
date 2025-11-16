# Gaussian Naive Bayes Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)

Apply probabilistic classification with Gaussian Naive Bayes. This notebook moves from Bayes theorem fundamentals to a working scikit-learn implementation, highlighting assumptions, probabilities, and decision boundaries.

## Notebook
- `Naive_Bayes_Algorithm.ipynb` – derives the Gaussian likelihood, implements the classifier by hand, and benchmarks against `sklearn.naive_bayes.GaussianNB` using visual diagnostics.

## Highlights
- Understand conditional independence assumptions and when they hold in practice.
- Compute class priors, likelihoods, and posterior probabilities step-by-step in NumPy.
- Interpret model confidence with probability heatmaps and misclassification analysis.

## Requirements
- Python 3.9+
- Packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
```powershell
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook "Naive_Bayes_Algorithm.ipynb"
```
Follow the guided cells to generate synthetic data, fit the Bayesian classifier, and compare predictions.

## Extend the Notebook
- Introduce categorical features and evaluate how the Gaussian assumption breaks down.
- Add feature scaling or dimensionality reduction to see its impact on class separability.
- Compare Gaussian, Multinomial, and Bernoulli variants using the same dataset.

## SEO Keywords
`gaussian naive bayes tutorial`, `bayes theorem machine learning`, `probabilistic classifier notebook`, `scikit-learn gaussiannb example`, `naive bayes from scratch`

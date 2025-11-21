# Machine Learning Playground

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Built%20with-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Hands-on machine learning tutorials written as self-paced Jupyter notebooks with reproducible Python code, visual diagnostics, and step-by-step math intuition.

## Overview
Machine Learning Playground curates algorithm-focused notebooks that demystify foundational models. Every lesson blends plain-language explanations, annotated Python implementations, and crisp plots so you can translate theory into working code quickly. Whether you are revising core concepts or preparing for interviews, the notebooks are built to be forked, tweaked, and extended.

## Why Explore This Repo
- Strengthen machine learning fundamentals with notebooks that walk through derivations and code line-by-line.
- Validate intuition by comparing from-scratch numpy implementations with scikit-learn baselines.
- Experiment confidently using clean, reproducible datasets and clearly labelled code cells.
- Build a public ML portfolio by customising visuals, tuning hyperparameters, and documenting findings.

## Repository Structure
- `Decision Trees/` – Visualise decision boundaries and interpret splits with `dtreeviz`.
- `Ensemble Learning/` – Compare bagging and voting ensembles across classification tasks.
- `Guassian Naive Bayes/` – Derive and apply Gaussian Naive Bayes from scratch and via scikit-learn.
- `K-Nearest Neighbours/` – Tune KNN on the Titanic dataset and inspect feature importance.
- `Linear_Regression/` – Walk through gradient descent updates for simple linear regression.
- `Logistic_Regression/` – Contrast logistic regression with perceptron-style classifiers.
- `Random Forest/` – Train tree-based ensembles on a heart-disease dataset and interpret feature importance.

## Quickstart
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn notebook dtreeviz
jupyter notebook
```
Open the desired `.ipynb` file from Jupyter Lab or Notebook and execute cells sequentially. Many notebooks include optional experiments in markdown cells—tweak parameters and re-run to observe the impact instantly.

## Technologies
- Python 3.9+
- Jupyter Notebook / JupyterLab
- NumPy, pandas, Matplotlib, Seaborn
- scikit-learn, dtreeviz (for decision tree visualisations)

## Learning Roadmap
- Solidify regression intuition with `Linear_Regression/Gradient-descent-step-by-step.ipynb`.
- Master binary classification using `Logistic_Regression/Gradient_Descent_Logistic_Regression.ipynb`.
- Explore non-parametric methods via `K-Nearest Neighbours/KNN_on_Titanic_Dataset (1).ipynb`.
- Interpret tree-based models in `Decision Trees/Decision_Tree_visualization_using_dtreeviz.ipynb`.
- Ensemble your knowledge with bagging and voting notebooks under `Ensemble Learning/`.
- Deploy robust tree ensembles via `Random Forest/Random_Forest_on_Heart_disease.ipynb` and its from-scratch companion notebook.
- Round out probabilistic modelling inside `Guassian Naive Bayes/Naive_Bayes_Algorithm.ipynb`.

## Contributing
- Run notebooks from start to finish and clear execution errors before submitting pull requests.
- Document any new experiments in markdown so readers understand your rationale.
- Add screenshots or GIFs when you update visualisations or decision boundaries.
- Propose new folders for algorithms not yet covered and include a README that follows the existing style.

## License
This project is released under the [MIT License](LICENSE).

## SEO Keywords
`machine learning tutorials`, `jupyter notebook machine learning`, `python gradient descent example`, `logistic regression from scratch`, `k nearest neighbors titanic`, `decision tree visualization dtreeviz`, `ensemble learning bagging voting`, `gaussian naive bayes tutorial`, `random forest heart disease`, `scikit-learn beginner projects`, `machine learning portfolio notebooks`

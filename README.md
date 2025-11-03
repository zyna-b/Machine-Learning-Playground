# Machine Learning Playground

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Machine learning notebook tutorials focused on gradient descent, linear regression, logistic regression, and perceptron algorithms. Each walkthrough balances mathematical intuition with hands-on Python code so you can see every optimization step, visualize convergence, and compare results against scikit-learn baselines.

## Features
- End-to-end Jupyter notebooks optimized for interactive learning and self-paced study.
- Visual diagnostics that highlight decision boundaries, regression lines, and convergence curves.
- Reproducible experiments powered by NumPy, pandas, Matplotlib, and scikit-learn.
- Practical guidance on tuning learning rates, iteration counts, and stopping criteria for gradient descent.

## Included Notebooks
- `Gradient-descent-step-by-step.ipynb`: Demystifies gradient descent for simple linear regression with side-by-side comparisons to ordinary least squares.
- `Gradient_Descent_Logistic_Regression.ipynb`: Implements logistic regression from scratch, validating the routine against scikit-learn's `LogisticRegression` estimator.
- `Logistic-Regression-Perceptron-trick-sigmoid.ipynb`: Explores step-activation and sigmoid perceptrons alongside a logistic regression baseline on the same synthetic dataset.

## Quick Start
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy matplotlib pandas scikit-learn seaborn notebook
jupyter notebook Gradient-descent-step-by-step.ipynb
```
Launch the remaining notebooks from the Jupyter interface to dive into logistic regression and perceptron experiments.

## Roadmap
- Add mini-projects for stochastic gradient descent, momentum, and adaptive optimizers.
- Introduce notebooks covering support vector machines, k-nearest neighbors, and ensemble techniques.
- Release real-world dataset case studies that extend beyond synthetic examples.

## Contributing
- Run notebooks top-to-bottom before submitting changes to keep outputs reproducible.
- Document new experiments and parameter tweaks directly inside notebooks for readers.
- Open a pull request summarizing your additions and attach screenshots if visuals change.

## License
This project is released under the [MIT License](LICENSE).

More machine learning algorithm implementations will continue to land here as the playground grows.

## SEO Keywords
`machine learning tutorial`, `gradient descent notebook`, `linear regression from scratch`, `logistic regression step by step`, `perceptron vs logistic regression`, `python machine learning playground`, `scikit-learn gradient descent`, `interactive machine learning notebooks`

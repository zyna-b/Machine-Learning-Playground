# Machine Learning Playground

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-FF6F00?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A growing collection of hands-on machine learning tutorials delivered as Jupyter notebooks. Each folder focuses on a foundational algorithm—linear regression, logistic regression, perceptrons—with clear math, reproducible code, and visual diagnostics. New algorithms and optimization strategies will continue to join the playground as the project expands.

## Overview
- Build intuition for classic ML algorithms by combining derivations, Python implementations, and plotted outcomes.
- Compare from-scratch gradient descent updates against scikit-learn baselines to validate results.
- Experiment safely with hyperparameters thanks to synthetic yet easily extensible datasets.

## Repository Map
- `Linear_Regression/`: Gradient descent for simple linear regression with line-by-line visualizations. See `Linear_Regression/README.md` for details.
- `Logistic_Regression/`: Logistic regression and perceptron notebooks that contrast activations and optimization behaviour. See `Logistic_Regression/README.md` for details.

## Getting Started
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn notebook
jupyter notebook
```
Open any notebook from the Jupyter file browser to explore the workflow end-to-end.

## Roadmap
- Add notebooks for stochastic gradient descent, momentum, and adaptive optimizers.
- Document classification algorithms such as support vector machines, k-nearest neighbors, and decision trees.
- Incorporate real-world datasets and lightweight evaluation pipelines for benchmarking.

## Contributing
- Run notebooks from top to bottom before opening a pull request so outputs stay reproducible.
- Explain any new experiments or parameter sweeps inside markdown cells for reader context.
- Include screenshots when your contribution updates visualizations or convergence plots.

## License
This project is released under the [MIT License](LICENSE).

## SEO Keywords
`machine learning tutorial`, `gradient descent notebook`, `linear regression from scratch`, `logistic regression step by step`, `perceptron vs logistic regression`, `python machine learning playground`, `scikit-learn tutorials`, `interactive machine learning notebooks`

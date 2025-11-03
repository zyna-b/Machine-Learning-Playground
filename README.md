# Gradient Descent for Logistic Regression

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-green.svg)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A hands-on notebook that demonstrates how to implement logistic regression with gradient descent from scratch, compare it with scikit-learn, and visualize the resulting decision boundaries. Ideal for learners searching for a practical gradient descent tutorial focused on binary classification workflows.

## Overview
- Builds a linearly separable synthetic dataset with `sklearn.datasets.make_classification` for controlled experiments.
- Trains two classifiers: a custom gradient descent implementation and scikit-learn's `LogisticRegression` for benchmarking.
- Visualizes model coefficients, the learned hyperplane, and the convergence behavior to cement intuition about logistic regression optimization.

## Features
- Step-by-step gradient descent loop for logistic regression weight updates.
- Clear mathematical breakdown of intercept and slope extraction from trained models.
- High-resolution scatter plots and decision boundary overlays using Matplotlib.
- Easily adjustable learning rate, iteration count, and dataset parameters for experimentation.

## Project Structure
```
Gradient_Descent_Logistic_Regression.ipynb  # Main notebook with code, plots, and explanations
venv_py39/                                  # (Optional) Local virtual environment
```

## Getting Started
1. **Clone the repository**
   ```powershell
   git clone https://github.com/<your-user>/Deep-Learning-Perceptron-Implementation.git
   cd Deep-Learning-Perceptron-Implementation
   ```
2. **Create and activate a virtual environment (recommended)**
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
3. **Install the required packages**
   ```powershell
   pip install numpy matplotlib scikit-learn seaborn
   ```
4. **Launch Jupyter Lab or Notebook**
   ```powershell
   jupyter notebook Gradient_Descent_Logistic_Regression.ipynb
   ```

## Usage Tips
- Adjust `learning rate`, `iterations`, and `class_sep` inside the notebook to observe their impact on convergence.
- Compare the custom gradient descent coefficients against scikit-learn's implementation to validate correctness.
- Enable inline plots (`%matplotlib inline`) if you open the notebook in a different environment.

## Results and Visualization
The notebook renders:
- Scatter plots that color-code the synthetic binary classes.
- Decision boundary overlays for both the custom and scikit-learn models.
- Printed intercepts and coefficients to highlight matching solutions.

## Roadmap Ideas
- Add loss tracking to visualize convergence curves.
- Introduce regularization and momentum to the gradient descent procedure.
- Extend the notebook to multi-class logistic regression or real-world datasets.

## Contributing
1. Fork the project and create a feature branch.
2. Format notebook cells or scripts before committing.
3. Submit a pull request describing your updates and attach sample outputs if visualizations change.

## License
This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/) for visualization utilities.
- Inspiration from classic gradient descent tutorials used in introductory machine learning courses.

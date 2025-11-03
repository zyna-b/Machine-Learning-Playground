# Machine Learning Playground

Hands-on notebooks that explore gradient descent for both linear and logistic regression, along with perceptron variants. Every notebook runs top-to-bottom so you can review the derivations, code, and visual output in a single pass.

## Included Notebooks
- `Gradient-descent-step-by-step.ipynb` walks through gradient descent for simple linear regression, compares it with the ordinary least squares solution, and visualizes how the line converges.
- `Gradient_Descent_Logistic_Regression.ipynb` implements logistic regression with gradient descent from scratch and benchmarks the result against scikit-learn's `LogisticRegression` estimator.
- `Logistic-Regression-Perceptron-trick-sigmoid.ipynb` contrasts a hard-threshold perceptron with a sigmoid-activated variant and the scikit-learn baseline on the same dataset.

## What You'll Practice
- Generating reproducible synthetic datasets with `sklearn.datasets` for binary classification and regression tasks.
- Deriving and coding gradient updates for intercepts and coefficients in both linear and logistic settings.
- Visualizing convergence, decision boundaries, and regression lines with Matplotlib to build intuition about optimization behaviour.

## Quick Start
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy matplotlib scikit-learn pandas seaborn notebook
jupyter notebook Gradient-descent-step-by-step.ipynb
```
Open the remaining notebooks from the Jupyter file browser to explore the logistic regression and perceptron workflows.

## Contributing
- Run notebooks end-to-end before committing so outputs stay consistent and reproducible.
- Document new experiments or parameters inside the notebooks so readers can follow along with your changes.
- Submit a pull request explaining the motivation behind your updates and include screenshots if the visuals differ from the baseline outputs.

## License
This project is released under the [MIT License](LICENSE).

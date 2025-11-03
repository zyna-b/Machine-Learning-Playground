# Machine Learning Playground

Hands-on notebooks that explore gradient descent, logistic regression, and perceptron variants. Each notebook runs top-to-bottom so you can inspect the math, code, and visualizations in one place.

## Notebooks
- `Gradient_Descent_Logistic_Regression.ipynb` implements logistic regression with gradient descent and compares it against scikit-learn's `LogisticRegression` estimator.
- `Logistic-Regression-Perceptron-trick-sigmoid.ipynb` contrasts a classic perceptron with a sigmoid-activated variant and the scikit-learn baseline on the same synthetic dataset.

## Key Ideas
- Build linearly separable datasets with `sklearn.datasets.make_classification` for reproducible experiments.
- Visualize decision boundaries, convergence behaviour, and learned coefficients with Matplotlib.
- Experiment with learning rates, iteration counts, and activation functions to see how optimization choices influence the models.

## Quick Start
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy matplotlib scikit-learn notebook seaborn
jupyter notebook Gradient_Descent_Logistic_Regression.ipynb
```
Open the second notebook from the Jupyter file browser to explore the perceptron-focused workflow.

## Contributing
- Run notebooks end-to-end before committing to ensure outputs are reproducible.
- Document new experiments or parameters inside the notebooks so readers can follow along.
- Submit a pull request that describes the motivation behind your changes and includes any new visuals if they differ from the baseline outputs.

## License
This project is released under the [MIT License](LICENSE).

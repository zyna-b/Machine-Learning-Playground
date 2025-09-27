# Logistic Regression Perceptron Trick with Sigmoid

Understand binary classification by building a complete workflow that compares a classic perceptron trained with a step activation against a sigmoid-based variant and scikit-learn's logistic regression baseline.

## 📌 Overview
- **Domain keywords:** logistic regression, perceptron trick, sigmoid activation, binary classification, scikit-learn, numpy, matplotlib, machine learning visualization.
- Generate a perfectly separable synthetic dataset with `make_classification` and explore learning dynamics across three decision boundaries.
- Reproduce the experiment end-to-end inside the companion notebook `Logistic-Regression-Perceptron-trick-sigmoid.ipynb`.

## ✨ Feature Highlights
- Step-by-step perceptron implementation using a hard step function.
- Sigmoid-activated perceptron illustrating smooth probability outputs.
- Comparison with `sklearn.linear_model.LogisticRegression` for a production-ready baseline.
- Rich matplotlib plots that overlay all decision lines for instant visual diagnostics.
- Clean, reproducible experiment powered by Python 3.9 and mainstream scientific libraries.

## 🧱 Project Structure
```
.
├── Logistic-Regression-Perceptron-trick-sigmoid.ipynb  # Main experiment notebook
├── README.md                                           # Project documentation (you are here)
└── venv_py39/                                          # Optional local virtual environment
```

## 🚀 Quick Start
### Prerequisites
- Python 3.9+
- PowerShell or another terminal capable of running Python virtual environments

### Set up a virtual environment
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy matplotlib scikit-learn
```

### Launch the notebook
```powershell
pip install notebook
jupyter notebook Logistic-Regression-Perceptron-trick-sigmoid.ipynb
```

## 📒 Notebook Walkthrough
1. **Data Generation:** Builds a 2D, linearly separable dataset with wide class separation for clarity.
2. **Perceptron (Step Function):** Implements the perceptron update rule with a binary step activation.
3. **Logistic Regression Baseline:** Fits `LogisticRegression` from scikit-learn as a benchmark decision boundary.
4. **Perceptron (Sigmoid):** Reuses the perceptron training loop with a sigmoid activation to produce probabilistic outputs.
5. **Visualization:** Plots all three decision boundaries alongside the data to compare slopes and intercepts.
6. **Interpretation:** Discusses similarities between the approaches and hints at when each method is preferable.

## 🔍 Results & Interpretation
- The perceptron with a step function converges quickly on linearly separable data but provides no calibrated probabilities.
- Logistic regression and the sigmoid-based perceptron generate smoother transitions across the boundary, ideal for probabilistic reasoning.
- In this controlled dataset the decision lines are nearly identical, underscoring that optimization strategy often matters more on noisier data.

## 📈 Extend the Experiment
- Add noise to `make_classification` via `flip_y` and observe the effect on perceptron convergence.
- Swap in alternative learning rates or epochs to probe stability.
- Experiment with higher-dimensional feature spaces and visualize using principal components.

## 🤝 Contributing
Pull requests are welcome! Feel free to:
- Refine visualizations
- Add alternative optimization algorithms (e.g., stochastic gradient descent with momentum)
- Incorporate evaluation metrics such as accuracy or AUC

Before submitting changes, ensure the notebook executes top-to-bottom without errors.

## 📄 License
This project is distributed under the terms of the [MIT License](LICENSE).

## 📬 Contact & SEO Keywords
For questions or suggestions, open an issue or reach out to the project maintainer.

**Keywords:** Logistic Regression tutorial, Perceptron algorithm Python, Sigmoid activation example, Binary classification visualization, scikit-learn logistic regression notebook, perceptron vs logistic regression, machine learning decision boundary plotting.

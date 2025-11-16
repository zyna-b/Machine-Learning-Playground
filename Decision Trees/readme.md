# Decision Trees Module

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![dtreeviz](https://img.shields.io/badge/dtreeviz-2.x-006600)](https://github.com/parrt/dtreeviz)

Visualise how decision trees split data using `dtreeviz` and scikit-learn. This module focuses on interpreting model structure, tracing decision paths, and communicating predictions with publication-ready visuals.

## Notebook
- `Decision_Tree_visualization_using_dtreeviz.ipynb` – trains a classification tree, inspects feature importance, and renders interactive plots that explain each branch and leaf.

## Highlights
- Learn to configure scikit-learn's `DecisionTreeClassifier` for clear, interpretable structures.
- Use `dtreeviz` to generate feature-space charts, node-level explanations, and what-if analyses.
- Compare tree depth, impurity metrics, and pruning strategies to balance accuracy and interpretability.

## Requirements
- Python 3.9+
- Packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `dtreeviz`

## How to Run
```powershell
pip install numpy pandas matplotlib seaborn scikit-learn dtreeviz
jupyter notebook "Decision_Tree_visualization_using_dtreeviz.ipynb"
```
Execute the notebook sequentially to load data, fit the model, and render the visualisations.

## Try These Experiments
- Adjust `max_depth`, `min_samples_split`, or `criterion` to observe how decision boundaries evolve.
- Swap the dataset for one of your own (ensure categorical features are encoded) and regenerate the tree visuals.
- Export `dtreeviz` outputs as SVG or PNG to embed them in reports and slide decks.

## SEO Keywords
`decision tree visualization`, `dtreeviz tutorial`, `interpretable machine learning notebook`, `scikit-learn decision tree example`, `explainable ai python`

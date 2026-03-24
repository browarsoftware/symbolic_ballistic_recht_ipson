### Source codes for paper:

# Analytical formulae for two-dimensional ballistic limit curves \\in the range of material thickness based on Recht-Ipson model and symbolic regression


This repository contains a collection of Jupyter notebooks and results. Each notebook is self-contained and includes explanations, code, and visualizations.

## 📂 Contents

### 🌲 Ensemble Models
- [**random_forest.ipynb**](random_forest.ipynb)
  Implementation and analysis of a Random Forest model.

- [**xgboost.ipynb**](xgboost.ipynb)
  Gradient-boosted decision trees using XGBoost.

### 🔢 Symbolic Regression
- [**symbolic_regression.ipynb**](symbolic_regression.ipynb)
  Exploration with symbolic regression.

- [**symbolic_regression_R-I.ipynb**](symbolic_regression_R-I.ipynb)
  Exploration with symbolic regression constrained by Recht-Ipson model.


---

## 📁 Additional Folders

### [**data/**](data/)
Data can be made available on reasonable request.  

### [**errors_for_wilcoxon/**](errors_for_wilcoxon/)
Contains error distributions used for statistical testing.  

### [**results/**](results/)
Contains generated outputs from the experiments, pickled models and equations.

### [**tables/**](tables/)
Stores tabular results for LaTeX.


### 📦 Dependencies
- [**requirements.txt**](requirements.txt)
  Contains all Python dependencies needed to run the notebooks.  
  Install with:

  ```bash
	git clone https://github.com/browarsoftware/symbolic_ballistic_recht_ipson.git
	cd symbolic_ballistic_recht_ipson
	pip install -r requirements.txt
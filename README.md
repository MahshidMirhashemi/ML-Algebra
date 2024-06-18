# Application of Machine Learning in Computation of Pommaret Bases

This repository contains the source code for the paper [https://doi.org/10.1016/j.jsc.2024.102345]. In this project, we generated 10,000 ideals and their features, and computed the best elementary moves using volume polynomials. Using this dataset, we applied the following machine learning techniques:
- k-Nearest Neighbors (kNN)
- Support Vector Machine (SVM)
- Decision Tree (DT)
- Multilayer Perceptron (MLP)
- Logistic Regression (LR)

## Repository Structure

### Part 1: Sagemath

This folder focuses on producing the dataset and analyzing the results of each machine learning method. It also includes:
- Democratic and random strategy implementations
- Figures and information about the dataset and different methods

The Jupyter notebooks in this folder use Sagemath.

### Part 2: ML

This folder contains implementations of different machine learning methods for the given dataset. The Jupyter notebooks in this folder use Python.

### Part 3: Database

This folder will be uploaded soon!

## Usage

To produce a dataset in a polynomial ring with 4, 5, or 6 variables, follow these steps:

1. Open `Sagemath/0.Running_codes.ipynb`.
2. In the second cell, set `N` to the number of variables in the polynomial ring.
3. In the third cell, set `x2` to the number of ideals you want to produce.
4. Run all the cells in the notebook. You will generate three files:
   - `statistical_features.csv`
   - `theoretical_features.csv`
   - `outputs.csv`

All the information, including ideals, Gröbner bases, monomial Janet bases, and elementary moves, will be stored in the database files.

---

### Notes:
- Ensure that Sagemath is installed and properly configured for the Jupyter notebooks in the Sagemath folder.
- For the ML folder, ensure that Python and necessary libraries (like scikit-learn) are installed.

### Future Work
- Upload the `Database` folder with complete datasets and additional documentation.

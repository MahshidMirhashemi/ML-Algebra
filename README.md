# Application of Machine Learning in computation of Pommaret bases

This repository is the sorce code of the paper [link]. 
In this project, we produced a 10000 ideals and their feartures and computed the best elementary move using volume polynomials. 
By using this dataset, we applied the following machine techniques on the dataset
• k Nearest Neighbours (kNN)
• Support Vector Machine (SVM)
• Decision Tree (DT)
• Multilayer Perceptron (MLP)
• Logistic Regression (LR)

# Part 1: Sagemath folder

This part is focused on producing dataset and also studying the result of each ML methods output at the end. 
It also contains the democratic and random strategy, and some figures and information about the dataset and different methods. 
Sagemath has been used in the Jupyter notebooks of this folder.


# Part 2: ML

This folder contains different machine learning methods for the given dataset.
Python has been used in the Jupyter notebooks of this folder.


# Part 3: Database

will be uploaded soon!


## Usage

For producing dataset in a polynomial ring with 4, 5 or 6 variables, open Sagemath/0.Running_codes.ipynb.
In the second cell, set the number N as the number of varibales in the polynomial ring.
In the third cell, set x2 as the number of ideals you want to produce. 
After running all the cells, you will have 3 files
 • statistical_features.csv
 • theoritical_features.csv
 • outputs.csv
Also all the information including ideals, Grobner bases, monomial Janet bases and elementary moves will be stored in the database files. 

# Machine Learning Algorithms and Model Evaluation

A machine learning project focused on implementing and evaluating foundational supervised learning algorithms using Python and Scikit-learn.

This project explores:

K-Nearest Neighbours (KNN)
Ridge Regression
Logistic Regression
cross-validation
hyperparameter tuning
performance evaluation and visualization

Implemented as part of CIS*4780 – Computational Intelligence.

## Project Overview

The goal of this project was to build and analyze several classical machine learning algorithms on different datasets while comparing their performance using statistical evaluation metrics and visualization techniques.

The project includes:

classification
regression
model comparison
cross-validation
hyperparameter experimentation
ROC analysis

A strong emphasis was placed on:

analytical evaluation
visualization of results
understanding model behavior
comparing training and testing performance
### Part 1 — K-Nearest Neighbours (KNN)

Implemented the K-Nearest Neighbours classification algorithm and evaluated its performance using 10-fold cross-validation.

Experiments included:

varying the number of neighbours (K)
Euclidean vs Manhattan distance metrics
training/testing accuracy comparison
overfitting and underfitting analysis

Visualizations were created to compare model accuracy across different K values.

### Part 2 — Ridge Regression

Implemented Ridge Regression on a housing dataset to predict retail property values.

Features included:

regularization using lambda hyperparameters
5-fold cross-validation
Mean Squared Error (MSE) and R² evaluation
hyperparameter experimentation and analysis

The project explored how regularization strength affects model performance and generalization.

### Part 3 — Logistic Regression

Implemented Logistic Regression for binary classification tasks.

Evaluation included:

training/testing accuracy
F-measure analysis
standard deviation across folds
model stability analysis
performance comparison across cross-validation runs

The project also explored which evaluation metrics best represent classifier performance.

### Part 4 — Model Comparison

Compared:

K-Nearest Neighbours
Logistic Regression

using:

error rates
ROC curves
cross-validation statistics
training/testing performance

Analysis focused on:

classification performance
generalization ability
parameter selection
model stability
## Technologies Used
Python
Scikit-learn
NumPy
Pandas
Matplotlib
Jupyter Notebook
## Skills Demonstrated
Supervised Learning
Classification
Regression
Cross-Validation
Hyperparameter Optimization
Statistical Evaluation
ROC Analysis
Data Visualization
Machine Learning Experimentation
## Repository Structure
assignment1/
├── a1.ipynb
├── datasets/
├── figures/
├── results/
└── README.md
## How to Run

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

## Open:

a1.ipynb

and run all cells.

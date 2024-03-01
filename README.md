# Easy Trick for Random Forest Model

This repository contains code for implementing a stacked ensemble regression model using scikit-learn library. The model is trained and evaluated on the Iris dataset.

## Description
- `RF with Linear Regression.ipynb`: This Jupyter Notebook contains code for importing necessary functions from scikit-learn, loading the Iris dataset, preprocessing the data, initializing base regression models (Random Forest and Linear Regression), creating and training a stacked ensemble regression model, and evaluating the model's accuracy.

## Usage
1. Download the Jupyter Notebook (`RF with Linear Regression.ipynb`) and ensure you have Jupyter Notebook installed.
2. Open the Notebook in Jupyter Notebook.
3. Run the cells in the Notebook to execute the code step by step.

## Dataset
The Iris dataset is used in this example, which is included in the scikit-learn library. The dataset contains features describing iris flowers and the target variable is the species of the iris.

## Stacked Ensemble Model
The stacked ensemble model combines predictions from multiple base regression models (Random Forest and Linear Regression in this case) to improve predictive performance. In this Notebook, the stacked model is created using `StackingRegressor` from scikit-learn.

## Results
After training the stacked ensemble model, its accuracy is evaluated using the test data. The accuracy score is displayed in the Notebook.

## Requirements
- Python 3
- Jupyter Notebook
- scikit-learn library

# Superconductivity Critical Temperature Prediction

## Overview

This project applies machine learning techniques to predict the critical temperature of superconducting materials based on their physicochemical properties.

The project was developed as part of the *Principles of Machine Learning* course at Universidad de los Andes, Colombia.

## Objectives

- Build predictive regression models to estimate the critical temperature of superconducting materials.
- Compare polynomial regression and Lasso regularization.
- Identify the physicochemical properties that contribute most to the predictions.
- Evaluate model performance using appropriate regression metrics.

## Dataset

The dataset contains physicochemical properties of superconducting materials, including atomic mass, atomic radius, density, and valence, along with their critical temperatures.

The dataset used in this project is a reduced and modified version of the original dataset.

**Original source:**

- Hamidieh, K. (2018). Superconductivty Data. UCI Machine Learning Repository.
- https://archive.ics.uci.edu/dataset/464/superconductivty+data

The modified dataset was provided by Universidad de los Andes for academic purposes.

## Methodology

The project follows a machine learning workflow:

1. Data exploration and profiling.
2. Data quality assessment.
3. Data cleaning and preprocessing.
4. Polynomial regression with model selection.
5. Lasso regression with hyperparameter selection.
6. Model evaluation and comparison.
7. Feature importance analysis.

## Models and Evaluation

The following approaches are explored:

- Polynomial Regression (degrees 2 and 3).
- Lasso Regression (alpha values from 1 to 5).

Models are evaluated using:

- R²
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Repository Structure

```text
superconductivity-critical-temperature-prediction/
│
├── data/
│   ├── Materiales_Superconductores.csv
│   └── diccionario_Materiales_Superconductores.xlsx
│
├── notebooks/
│   ├── microproyecto1.ipynb
│   └── microproyecto1.html
│
├── .gitignore
├── README.md
└── requirements.txt
```

### Files Description

| File / Directory | Description |
|---|---|
| `data/` | Dataset and data dictionary used in the project. |
| `notebooks/` | Jupyter Notebook containing the analysis and model development, along with its HTML export. |
| `.gitignore` | Specifies files and directories excluded from Git tracking. |
| `README.md` | Project overview, methodology, and documentation. |
| `requirements.txt` | Python dependencies required to run the project. |

## Academic Context

Developed as an academic project for the Master's program in Artificial Intelligence at Universidad de los Andes.

## Acknowledgements

Credit to Kam Hamidieh and the UCI Machine Learning Repository for the original dataset, and to Universidad de los Andes for the academic adaptation.

The dataset materials indicate a Creative Commons license. Refer to the original source and applicable licensing terms for attribution and redistribution conditions.

# TDSE-01
# Stellar Luminosity Regression Project

This project implements linear and polynomial regression from scratch to model stellar luminosity as a function of mass and temperature. No machine learning libraries are used; all prediction, loss, and gradient descent functions are implemented with NumPy. The project is part of a Machine Learning Bootcamp within a course on Digital Transformation and Enterprise Architecture.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Python 3.x
Jupyter
```

### Installing

```
1. Clone the repository
2. Activate an environment.
```


## Running the notebooks

1. Notebook 1 (01_part1_linreg_1feature.ipynb)

    - Models luminosity as a linear function of stellar mass

    - Includes data visualization, cost surface, gradient descent (vectorized and non-vectorized), learning rate experiments, and final line fit

2. Notebook 2 (02_part2_polyreg.ipynb)

   - Models luminosity considering mass, temperature, and polynomial terms (M², M*T)

    - Includes feature engineering, vectorized gradient descent, feature selection experiments, interaction term analysis, and prediction for new stars

### AWS SageMaker Execution Evidence

Explain what these tests test and why

```
Give an example
```

## Built With

* Python
* Jupyter

## Authors

* **Andres Felipe Cardozo Martinez**

## Acknowledgments

* This project was guided by laboratory notebook exercises provided as part of the course.


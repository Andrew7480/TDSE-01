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

Amazon SageMaker is a fully managed cloud service from AWS that enables developers and data scientists to quickly and scalably create, train, and deploy machine learning (ML) and generative AI models.


1. Upload process

<img width="1583" height="742" alt="image" src="https://github.com/user-attachments/assets/cd28e490-958f-4735-97b5-da158b6776e2" />

Both notebooks (01_part1_linreg_1feature.ipynb and 02_part2_polyreg.ipynb) were uploaded to AWS SageMaker Studio

<img width="255" height="140" alt="image" src="https://github.com/user-attachments/assets/affc4dd1-59d0-48e4-a7f9-eebbbbae800a" />

2. Execution
No errors occurred during execution.

<img width="350" height="52" alt="image" src="https://github.com/user-attachments/assets/5aa5009f-f744-4352-87a1-b044c26d1968" />

<img width="861" height="670" alt="image" src="https://github.com/user-attachments/assets/38131bf2-0118-49b7-8fe6-2501b5034766" />

<img width="768" height="668" alt="image" src="https://github.com/user-attachments/assets/f5884355-290a-4a9c-a634-fb75b706232b" />


## Built With

* Python
* Jupyter

## Authors

* **Andres Felipe Cardozo Martinez**

## Acknowledgments

* This project was guided by laboratory notebook exercises provided as part of the course.


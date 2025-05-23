# Fourier Neural Operator for Navier-Stokes Equation

## Overview
This repository is based on the original implementation of the Fourier Neural Operator (FNO), available at [neuraloperator/neuraloperator](https://github.com/neuraloperator/neuraloperator.git). The theoretical foundation is presented in the following paper:

**Original Paper: "Fourier Neural Operator for Parametric Partial Differential Equations"**  
[Paper Link](https://arxiv.org/abs/2010.08895)  
Authors: Zongyi Li, Nikola Kovachki, Kamyar Azizzadenesheli, Burigede Liu, Kaushik Bhattacharya, Andrew Stuart, Anima Anandkumar

This repository adds some additional codes including NO models, data and loss models from [neuraloperator/neuraloperator](https://github.com/neuraloperator/neuraloperator.git) to facilitate further research and study.

## Installation
The required `neuralop` library can be installed following the instructions provided in the official documentation:  
[Installation Guide](https://neuraloperator.github.io/dev/install.html)

## Navier-Stokes Data
The dataset for the Navier-Stokes equation is available for download from Zenodo:  
[Zenodo Dataset](https://zenodo.org/records/12825163)

## My Codes for Examples
- **`Examples/NS_Equation_spec.ipynb`**: This notebook applies spectrum analysis to study the distribution of energy across different scales in a fluid flow.
- **`Examples/NS_FNO_LOSS.ipynb`**: This notebook implements an FNO-based training setup for solving the Navier-Stokes equation with the Zenodo dataset.

## Computational Setup
The provided implementation is tested on a **CPU**. For better performance, using a **GPU** is highly needed.

## Acknowledgments
This project is built upon the original Fourier Neural Operator framework, and all credits go to the authors of the original paper and the contributors to the `neuraloperator` repository.


# Credit-Risk-Classification
## Overview

Welcome to the Loan Status Prediction GitHub repository! This repository contains code for building, evaluating, and comparing logistic regression models to predict loan status. The analysis involves using both the original data and resampled data for enhanced predictive performance.

## Table of Contents:
- [Overview](##Overview)
- [Instruction](##Instructions)
- [Results and Analysis](##ResultsandAnalysis)
- [Acknowledgements](##Acknowledgemnets)
- [Authors](#authors)

## Instructions
### Getting Started
- Clone the repository to your local machine:
- Navigate to the project directory:
### Code Execution
- Ensure you have the necessary dependencies installed:
    - numpy
    - pandas
    - scikit-learn
    - imbalanced-learn
- Run the code:
- Review the output in the console, including accuracy scores, confusion matrices, and classification reports.
### Understanding the Results
- The original logistic regression model's performance is detailed in the first part of the README, including accuracy scores and classification metrics.
- The second part involves oversampling the training data using the Random Over-sampling technique and comparing the logistic regression model's performance on the resampled data.

## Results and Analysis
### Original Model
The original logistic regression model demonstrates high accuracy in predicting both healthy and high-risk loans. Detailed metrics, including balanced accuracy scores, confusion matrices, and classification reports, are provided.
### Model with Resampled Data
The logistic regression model trained on oversampled data showcases improved performance, particularly in addressing the initial imbalance in the dataset. Enhanced sensitivity (recall) for both healthy and high-risk loans is observed, along with improved precision and F1-score.

## Acknowledgments:<a name="acknowledgemnets"></a>
### Code Support:
- supporting documentation from UT Austin The Data Analytics and Visualization Bootcamp at https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-DATA-PT-08-2023-U-LOLC/-/tree/main

## Authors:<a name="authors"></a>
- AC2BARRETO
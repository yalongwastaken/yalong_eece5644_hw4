# yalong_eece5644_hw4
**Author:** Anthony Yalong  
**NUID:** 002156860  
**Course:** EECE5644

## Assignment Overview
This repository contains the Python implementations, mathematical derivations, and report for Homework 4.

## Project Directory
```
yalong_eece5644_hw4/
├── problem1/                  # Contains all relevant synthesized work for Question 1
├── problem2/                  # Contains all relevant synthesized work for Question 2
├── .gitignore                 # GitHub formatting
├── README.md                  # This file
└── yalong_eece5644_hw4.pdf    # Complete report with results and analysis
```

## Requirements
- numpy
- matplotlib
- scikit-learn
- Pillow
- requests

All packages are pre-installed in Google Colab.

## Implementation Details

### Question 1:
SVM and MLP classifiers for overlapping concentric disk data (r=2, r=4, σ=1). K-fold cross-validation selects optimal hyperparameters (SVM: gamma/C, MLP: hidden neurons). Training: 1000 samples, Testing: 10000 samples.

### Question 2:
GMM-based image segmentation using 5D feature vectors [row, col, R, G, B]. K-fold cross-validation selects optimal components (K=2-20). Segments a Berkeley dataset image using maximum likelihood estimation and MAP assignment.

## Documentation
Complete analysis, mathematical derivations, results, and discussion are available in `yalong_eece5644_hw4.pdf`.

## Running the Code
Open the Jupyter notebooks in Google Colab.
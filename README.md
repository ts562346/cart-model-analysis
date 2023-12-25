# cart-model-analysis

## Overview

This R script is part of the STAT 2450 Assignment 6, focused on Classification with CART (Classification and Regression Trees). The analysis includes data preparation, model fitting, tree interpretation, plotting, testing errors, cross-validation, pruning, and comparison of training and testing errors.

## Getting Started

### Prerequisites

Make sure you have R and the necessary libraries installed. The script uses the `tree` library for fitting CART models.

```R
install.packages("tree")
library(tree)
```

### Data

Download the dataset `data6a.csv` from BS and use the provided R script to read the data.

```R
d <- read.csv(file='data6a.csv')
```

## Sections

### 1. Preparing the Data

- Identify and redefine categorical predictors as factors.
- Rename a specific column.
- Split the data into training and testing sets.

### 2. Model Fitting

- Fit a CART model to the training data.
- Obtain summary statistics about the tree.
- Interpret the tree.

### 3. Plotting the Tree

- Create a plot of the tree.
- Explain the meaning of the first node split.

### 4. Testing Errors

- Predict the response on the testing data.
- Produce a confusion matrix and calculate the testing error rate.

### 5. Cross-Validation

- Apply cross-validation to determine the optimal tree size.
- Plot the cross-validated classification error rate.

### 6. Pruning

- Produce a pruned tree based on the optimal tree size.
- Compare training error rates for pruned and unpruned trees.

### 7. Gini Index and Information Gain

- Implement functions to calculate Gini index and information gain.
- Check the functions with provided data.

## Authors

- [Author Name]

## Acknowledgments

- This script is part of a statistical analysis assignment for STAT 2450.

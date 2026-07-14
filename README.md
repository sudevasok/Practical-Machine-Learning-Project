# Practical Machine Learning Course Project

## Objective

This project predicts the manner in which participants performed barbell
lifts using accelerometer data.

The target variable is the `classe` variable.

## Dataset

The dataset contains accelerometer measurements from six participants
performing barbell lifts in five different ways.

## Machine Learning Method

A Random Forest classification model was developed.

Reasons for selecting Random Forest:

- Handles many predictor variables
- Works well with nonlinear relationships
- Provides high prediction accuracy
- Does not require feature scaling

## Validation

The training dataset was divided into:

- 75% training data
- 25% validation data

The model achieved approximately 99% accuracy.

The estimated out-of-sample error was approximately 1%.

## Files

- PML_Project.Rmd - R Markdown source file
- PML_Project.html - HTML report

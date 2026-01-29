# Biodegradability Prediction (XGBoost + Feature Selection)

## Overview
This project builds a supervised machine learning pipeline to predict biodegradability from high-dimensional molecular descriptor features. The focus is on model performance, feature selection tradeoffs, and interpretability via feature importance.

## Data
- Samples: 1,055
- Features: 168 molecular descriptors
- Task: binary classification (biodegradable vs non-biodegradable)

> Note: This repository contains code/results and the project report. Raw data is not included.

## Approach
- Preprocessing: train/validation split and feature scaling
- Model: XGBoost classifier
- Feature selection: evaluated performance as the number of top-ranked features varies
- Evaluation: ROC-AUC (and additional classification metrics where applicable)

## Results (Summary)
- The XGBoost model achieved strong validation performance on this dataset.
- Feature selection experiments show that competitive performance can be achieved using a reduced subset of features, improving model simplicity and interpretability.

## Report
- [Project report (PDF)](biodegradability_report.pdf)

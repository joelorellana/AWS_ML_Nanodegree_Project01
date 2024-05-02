# AWS_ML_Nanodegree_Project01
# Predict Bike Sharing Demand with AutoGluon

This repository hosts the project I completed for my AWS Machine Learning Nanodegree from Udacity, focusing on predicting bike sharing demand using AutoGluon, an automated machine learning solution by AWS.

## Overview

The project explores various stages of machine learning workflows including initial training, exploratory data analysis, feature engineering, and hyperparameter tuning. The main dataset involves bike sharing usage patterns, and the objective is to predict demand based on various environmental and temporal features.

## Key Findings

- Initial training used `medium_quality_faster_train` preset in AutoGluon for a balance between training time and model quality.
- Feature engineering was critical, with datetime split into smaller intervals significantly impacting model performance.
- Hyperparameter tuning further improved the model, showcasing the effectiveness of iterative refinements.

## Results

The model performance improved across several metrics through stages:
1. Initial training
2. Adding features
3. Hyperparameter tuning

The project includes detailed explorations of model performance and adjustments, culminating in a submission to a Kaggle competition.

## File Descriptions

- `project_notebook.ipynb`: Jupyter notebook containing the full workflow from data preprocessing to model training and evaluation.
- `project_report.md`: Comprehensive report detailing the project's methodologies, findings, and results.
- `model_train_score.png`: Visual representation of model improvement over the training iterations.
- `model_kaggle_score.png`: Tracking of model scores across different Kaggle submission attempts.

## Technologies Used

- AWS SageMaker
- AutoGluon
- Python
- Jupyter Notebooks

## Installation

To replicate or explore the project:

```bash
git clone https://github.com/[your-username]/predict-bike-sharing-demand-autogluon.git
cd predict-bike-sharing-demand-autogluon
Run the notebook to see the step-by-step process

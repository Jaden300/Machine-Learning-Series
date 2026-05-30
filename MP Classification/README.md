# Mobile Price Classification Notebook

**Author:** J. Wong  
**Date:** 2026-02-09  

This repository contains a **Jupyter Notebook** that demonstrates a complete machine learning workflow on the **Mobile Price Classification dataset**. The goal is to **predict the `price_range`** of mobile devices using multiple **classification algorithms** while balancing **performance and interpretability**.

## What’s Included

- **Data Import & Preprocessing**
  - Dataset inspection and cleaning
  - Feature/target correlation analysis
  - Multicollinearity checks
- **Exploratory Data Analysis**
  - Visualizations of feature distributions
  - Identification of most predictive features
- **Regression & Classification Modeling**
  - Logistic Regression (L1/L2, multinomial)
  - K-Nearest Neighbors (KNN) and elbow curve analysis
  - Support Vector Machines (Linear SVC, RBF SVC, GridSearch tuning)
  - Decision Trees (with and without GridSearch)
  - Ensemble methods:
    - Bagging
    - Random Forests (with GridSearch)
    - Extra Trees
    - Gradient Boosting, AdaBoost
    - Voting & Stacking Classifiers
    - XGBoost (including eval metrics & boosting iterations analysis)
- **Hyperparameter Tuning & Evaluation**
  - GridSearchCV
  - Cross-validation
  - Train/test splits
  - Metrics: Accuracy, Log Loss, Error Rate, ROC-AUC, Confusion Matrices
- **Model Interpretability**
  - Feature importance & permutation importance
  - Global surrogate models
  - LIME for local explanations

## Key Results

- Ensemble and boosting methods delivered **highest predictive performance**.  
- Features like `ram`, `battery_power`, `px_height`, and `px_width` were consistently **most influential**.  
- Models are both **accurate and explainable**, demonstrating a strong ML workflow.

## Dataset

- [Mobile Price Classification on Kaggle by A. Sharma](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)  
- Target variable: `price_range` (categorical price levels for mobile devices)

## Usage

- Open `Mobile_Price_Classification.ipynb` in Jupyter Notebook or Lab.  
- Run cells sequentially to reproduce **preprocessing, modeling, evaluation, and interpretation** steps.  
- Modify hyperparameters or models to experiment further.
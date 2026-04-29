# Prediction-of-Points-Table-of-a-Football-League-Using-Machine-Learning
## Basic overview

This is the repository for the project "Prediction of Points Table of a Football League Using Machine Learning". This repository contains:

## Dataset
The dataset consists of two publicly available datasets from Kaggle:

- Player Statistics Dataset (EPL 2023–24)
https://www.kaggle.com/datasets/orkunaktas/premier-league-all-players-stats-2324
- Match Statistics Dataset (EPL 2023–24)
https://www.kaggle.com/datasets/mertbayraktar/english-premier-league-matches-20232024-season

These datasets were merged and transformed into a team-level dataset through preprocessing and feature engineering, and used for training, validation, and testing of the models.

## Notebook
The notebook contains the full implementation of the project, including:
- Data loading and preprocessing
- Feature engineering and normalization
- Data visualization
- Model training (Decision Tree, Random Forest, KNN, SVM, AdaBoost, XGBoost)
- Hyperparameter tuning (GridSearchCV)
- Ensemble learning (Stacking)
- Model evaluation (Accuracy, Precision, Recall, F1-score)
- Explainable AI using LIME
- Handling imbalance using SMOTE

## Requirements for the model
- python
- numpy
- pandas
- scikit-learn
- xgboost
- imbalanced-learn
- lime
- matplotlib
- seaborn

## Getting the repository
This repository can be downloaded or cloned using:
git clone [https://github.com/LabibHasan01/Prediction-of-Points-Table-of-a-Football-League-Using-Machine-Learning.git](https://github.com/LabibHasan01/Prediction-of-Points-Table-of-a-Football-League-Using-Machine-Learning)
Or download it as a zip archive.

## Getting started with the code
After downloading or cloning the repository:
1. Open the notebook in Google Colab or Jupyter Notebook
2. Adjust file paths according to your dataset location (if needed)
3. Run all cells sequentially

## Data preprocessing and augmentation
In this notebook, the datasets are processed through multiple steps including:
- Aggregation of player data into team-level features
- Feature engineering (home/away statistics)
- Encoding categorical variables
- Z-score normalization
- Handling class imbalance using SMOTE

## Project Report
- Full report available in this repository.

Additional preprocessing and feature selection steps are included in the notebook and can be modified as needed. 

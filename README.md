# Fraud-Detection-System-for-Transactions

This project implements a machine learning model to detect fraudulent financial transactions using XGBoost with hyperparameter tuning and threshold optimization.

## Project Overview

The core of this project lies in handling the significant class imbalance typical in fraud detection datasets and optimizing model performance to effectively distinguish between legitimate and fraudulent E-Commerce and Bank transactions.

## Key Features

- Data preprocessing and feature engineering
- Handling class imbalance with `scale_pos_weight`
- XGBoost model with hyperparameter tuning using RandomizedSearchCV
- Threshold optimization for precision-recall tradeoff
- Interactive visualizations of model performance

## Results

Final model achieved:
- Accuracy: 99.96%
- Precision: 0.74
- Recall: 0.76
- F1-score: 0.73 (at threshold=0.675)

## Installation

1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Download dataset from [Kaggle](https://www.kaggle.com/datasets/...)

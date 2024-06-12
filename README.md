# Credit Card EDA and ML Correlation Findings

This repository contains code and data for performing exploratory data analysis (EDA) and applying machine learning (ML) techniques to find correlations in a credit card transactions dataset. The goal is to uncover valuable insights related to customer spending patterns, fraud detection, and targeted marketing strategies.

## Dataset

The dataset used in this project is a sample of anonymous credit card transactions, including fields such as transaction amount, merchant category, customer demographics, and timestamps. Due to privacy concerns, the actual dataset is not included in this repository. However, a subset of the data is provided in the `data/` directory for testing and demonstration purposes.

## Exploratory Data Analysis

The `eda/` directory contains Jupyter notebooks and Python scripts for exploratory data analysis, including:

- `transaction_distribution.ipynb`: Visualizes the distribution of transaction amounts and identifies potential outliers.
- `merchant_analysis.py`: Analyzes the distribution of transactions across different merchant categories.
- `customer_segmentation.ipynb`: Explores customer demographics and spending patterns for potential segmentation.
- `temporal_patterns.py`: Investigates temporal patterns in transaction data, such as day-of-week and seasonal effects.

## Machine Learning Models

The `models/` directory contains Python scripts and Jupyter notebooks for training and evaluating machine learning models on the credit card data:

- `fraud_detection.py`: Implements a classification model for detecting fraudulent transactions.
- `spending_prediction.ipynb`: Trains a regression model to predict transaction amounts based on customer and merchant features.
- `customer_clustering.py`: Applies clustering algorithms to segment customers based on their spending behavior.

## Setup

To run the code in this repository, you'll need Python 3.x and the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost (for some models)

You can install the required packages using `pip`:

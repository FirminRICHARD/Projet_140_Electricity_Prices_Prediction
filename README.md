# Project 140 - Electricity Prices Prediction

This repository contains a machine learning notebook for predicting the direction of the electricity price spread between intraday and day-ahead spot prices.

## Objective

The goal is to predict whether the intraday electricity price will be higher or lower than the day-ahead spot price.

Target used in the notebook:

```text
spot_id_delta = Intraday price - Spot price
target_direction = 1 if spot_id_delta > 0, else 0
```

## Contents

- `Projet_140_Electricity_Prices_Prediction.ipynb`: exploratory analysis, feature engineering, model training, validation, and final prediction workflow.
- `requirements.txt`: Python packages used by the notebook.

## Data

The notebook uses the following CSV files from the project root:

- `X_train_Wwou3IE.csv`
- `y_train_jJtXgMX.csv`
- `X_test_GgyECq8.csv`
- `y_random_pt8afo8.csv`

These files are included in this repository.

## Models

The notebook experiments with several classification models, including:

- Logistic Regression
- Random Forest Classifier
- HistGradientBoostingClassifier

## Setup

Install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook Projet_140_Electricity_Prices_Prediction.ipynb
```

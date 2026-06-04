### Joshi_et_al_2024_pco2_BoB_clim
## Citation
# Joshi, A. P., Ghoshal, P. K., Chakraborty, K., & Sarma, V. V. S. S. (2024). Sea-surface pCO2 maps for the Bay of Bengal based on advanced machine learning algorithms. Scientific Data, 11(1), 384.

## Creators
### Dr Apurva Padamnabh Joshi (A. P. Joshi) and Prasanna Kanti Ghoshal (P. K. Ghoshal)


## About

This repository contains Python scripts used to develop and evaluate machine learning models for predicting sea-surface pCO₂ from environmental variables.

The codes are intended for:

* Machine learning model development
* Hyperparameter tuning
* Model validation
* Predictor importance analysis
* Ensemble model generation
* Regional pCO₂ reconstruction

The repository serves as a collection of research codes used during the development of machine-learning-based pCO₂ products.

---

## Repository Contents

The repository contains scripts for:

### Data Preparation

* Reading observational datasets
* Preparing predictor variables
* Handling missing values
* Creating training and testing datasets

### Machine Learning Models

Implementation of multiple machine learning approaches, including:

* Random Forest Regression
* XGBoost Regression
* Gradient Boosting Regression
* Artificial Neural Networks

### Model Evaluation

Scripts for computing:

* Correlation coefficient (R)
* Root Mean Square Error (RMSE)
* Mean Absolute Error (MAE)
* Bias
* Cross-validation statistics

### Model Comparison

Tools for comparing the skill of different machine learning models and identifying the best-performing configuration.

### Ensemble Prediction

Generation of ensemble estimates from multiple model realizations.

---

## Input Data

The scripts require:

* Surface ocean pCO₂ observations
* Sea Surface Temperature (SST)
* Sea Surface Salinity (SSS)
* Chlorophyll-a concentration (Chl-a)
* Mixed Layer Depth (MLD)

Input data formats may need modification depending on the source datasets.

## Requirements

Python packages commonly used in the repository include:

```bash
numpy
pandas
scikit-learn
xgboost
scipy
joblib
matplotlib
xarray
netCDF4
```

Install dependencies using:

```bash
pip install -r requirements.txt
```

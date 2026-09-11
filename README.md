# Sunspot Time-Series Forecasting with MLP and GRU

Deep learning project for forecasting monthly sunspot activity using TensorFlow/Keras.

## Overview

This project compares two neural network approaches for time-series forecasting:

- Multilayer Perceptron (MLP)
- Gated Recurrent Unit (GRU)

The workflow includes data preprocessing, scaling, sequence preparation, model training, early stopping and performance evaluation.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## Models

The project trains and compares an MLP model and a GRU model using historical monthly sunspot data.

Model performance is evaluated using RMSE and MAE. In this experiment, the GRU achieved slightly better forecasting accuracy, while the MLP trained faster.

## Files

- `sunspot_forecasting.ipynb` – complete analysis and model training
- `data/sunspots.csv` – dataset used in the project

## Purpose

This project was developed as part of my MSc in Data Science and Machine Learning and demonstrates hands-on experience with deep learning and time-series forecasting.

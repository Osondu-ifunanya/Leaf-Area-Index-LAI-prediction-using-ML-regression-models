# 🌿 Leaf Area Index (LAI) Prediction using Machine Learning and Synthetic Data

## Overview
This project demonstrates the prediction of Leaf Area Index (LAI) using a Random Forest regression model trained on synthetic vegetation indices and spectral band data. It simulates remote sensing inputs and models plant canopy density.

## Dataset
- 1,000 synthetic samples
- Features: NDVI, EVI, Red, NIR, SWIR bands
- Target: Leaf Area Index (LAI)
- Noise added to mimic real-world uncertainty

## Model
- Random Forest Regressor from scikit-learn
- Evaluated using RMSE and R² score
- Visualized with scatter plot of actual vs predicted LAI

## Usage
1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib

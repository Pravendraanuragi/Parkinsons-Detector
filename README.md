# Parkinson's Disease Detector

This project implements a **Parkinson's Disease Detection system** using **XGBoost Classifier** in Python.  
The system predicts whether a patient is affected by Parkinson's disease based on speech measurements and biomedical features.

## Features

- **Pre-trained XGBoost Model:** JSON format, Colab-compatible
- **Feature Scaler:** StandardScaler saved using joblib
- **Dataset:** Parkinson's dataset used for training and testing
- **Prediction Testing:** Example patient prediction included
- **Accuracy Check:** Evaluate model performance on full dataset

## Usage

1. **Upload all files** (`parkinsons_xgb_model.json`, `scaler.pkl`, `parkinsons.data`, `Parkinsons_Detector.ipynb`) in Colab.  
2. Open `Parkinsons_Detector.ipynb` and run all cells.  
3. The notebook will load the model and scaler, check accuracy, and show example predictions.  
4. Optional: Test new patient data by adding a manual input row in the notebook.

## Folder Structure


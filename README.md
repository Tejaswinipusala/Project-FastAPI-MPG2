# MPG Prediction Project

## Overview
This project predicts car mileage (MPG) using Machine Learning.

## Features
- Data preprocessing
- Linear Regression model
- Pipeline implementation
- Model saved using joblib
- FastAPI for prediction

## How to Run

### Train Model
python train.py

### Run API
uvicorn app:app --reload

## Input Example
{
  "cylinders": 6,
  "displacement": 250,
  "horsepower": 100,
  "weight": 3300,
  "acceleration": 15,
  "model_year": 76,
  "origin": 1
}
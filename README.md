# Market Prediction Project

## Overview
Machine learning project for predicting market data using LSTM and hyperparameter optimization. Based on the Jane Street Market Prediction competition.

## Project Structure

´´´
market-prediction-jane-street/
├── data/
│   ├── raw/           # Original competition data
│   ├── processed/     # Processed datasets
│   ├── models/        # Trained models
│   └── predictions/   # Model predictions
│
├── notebooks/
│   ├── 01_EDA.ipynb                    # Exploratory analysis
│   ├── 02_Feature_Engineering.ipynb    # Feature creation
│   ├── 03_Preprocessing.ipynb          # Data preprocessing
│   ├── 04_Model_Development.ipynb      # Model implementation
│   ├── 05_Hyperparameter_Tuning.ipynb  # Model optimization
│   └── 06_Final_Prediction.ipynb       # Prediction generation
│
├── src/
│   ├── preprocessing.py    # Data preprocessing pipeline
│   ├── features.py         # Feature engineering functions
│   ├── models.py           # LSTM model implementation
│   ├── tuning.py           # Hyperparameter optimization
│   └── predict.py          # Prediction pipeline
│
├── tests/                  # Unit tests
│   ├── test_preprocessing.py
│   ├── test_features.py
│   └── test_models.py
│
├── requirements.txt
└── README.md
´´´

## Models Implemented

- LSTM (Long Short-Term Memory)
- Hyperparameter Optimization using Optuna
  - LSTM layers optimization
  - Learning rate tuning
  - Dropout rate optimization
  - Sequence length tuning



## Features

- Comprehensive data preprocessing
- Feature engineering for time series
- Hyperparameter optimization
- Cross-validation strategy
- Model performance analysis

## Installation
Clone repository
´´´
git clone https://github.com/yourusername/market-prediction.git

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
´´´

## Usage

- Run notebooks in order:
  - Start with EDA
  - Process through feature engineering
  - Perform hyperparameter tuning
  - Generate predictions

## Technologies Used

- Python 3.8+
- TensorFlow 2.x
- Optuna (Hyperparameter optimization)
- Pandas
- NumPy
- Scikit-learn

## Model Architecture

- LSTM layers (optimized count and units)
- Dropout layers (optimized rates)
- Dense output layer
- Adam optimizer with tuned learning rate

## Hyperparameter Optimization

- Number of LSTM layers: 1-3
- LSTM units per layer: 32-256
- Dropout rates: 0.1-0.5
- Learning rate: 1e-5 to 1e-2
- Batch size: [32, 64, 128]

## Results
[To be updated with model performance]

## License
MIT

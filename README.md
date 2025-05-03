# 🚖 Taxi Fare Prediction using Regression Models

This project explores various regression algorithms to predict taxi fare amounts from historical ride data. The goal is to evaluate and compare multiple models to determine which performs best in predicting fare prices.

## 📘 Project Overview

The dataset used includes features like trip distance, duration, and categorical data such as payment type and rate code. The target variable is `total_amount`, which represents the final fare charged.

The notebook includes:

- Data loading and preprocessing
- Feature encoding and scaling
- Model training and evaluation for multiple regression algorithms
- Performance comparison using R² Score and RMSE, MAE, MSE

## 🧠 Models Evaluated

The following regression models were implemented:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- K-Nearest Neighbors Regression

## 📁 Files

- `TaxiFares.ipynb` — Main notebook with code and visualizations
- `taxi_fares.csv` — Dataset file from kaggle
- `README.md` — Project overview and instructions

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib (for plots)

## 🚀 Getting Started

### Prerequisites

Install required packages:

```bash
pip install pandas numpy scikit-learn matplotlib
```

### Run the Notebook

1. Clone the repository:

```bash
git clone https://github.com/mouni-2502/AI_Taxi_Fares_Prediction.git
cd AI_Taxi_Fares_Prediction
```

2. Launch the notebook:

```bash
jupyter notebook TaxiFares.ipynb
```

## 📊 Evaluation Metrics

Each model is evaluated using:

- R² Score
- Root Mean Square Error (RMSE)
- Mean Square Error (MSE)
- Mean Absolute Error (MAE)

These metrics help identify the most accurate and generalizable model for taxi fare prediction.

## Results

- Linear Regression performs exceptionally well on this dataset.
- KNN performs relatively poorly, suggesting it's not a good fit for the taxi fare prediction problem in this case.

## 📌 Future Work

- Integrate hyperparameter tuning
- Add cross-validation for robust comparison
- Include advanced models like XGBoost or LightGBM

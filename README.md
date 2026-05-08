# Vehicle Price Prediction Using Machine Learning

## Project Overview

This project develops a machine learning system to predict vehicle prices using structured automotive data.

The system analyzes vehicle specifications such as mileage, engine details, make, model, transmission, drivetrain, and manufacturing year to estimate vehicle prices.

The project compares multiple regression models and evaluates their performance using standard regression metrics.

---

## Dataset Description

The dataset contains information about vehicles including:

- Vehicle make and model
- Manufacturing year
- Mileage
- Engine specifications
- Cylinders
- Fuel type
- Transmission
- Drivetrain
- Vehicle body type
- Exterior and interior colors
- Vehicle price

Target Variable:
- price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

## Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis

---

## Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## Evaluation Metrics

The following regression metrics were used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Generated Outputs

The project generates:

- Price Distribution Plot
- Mileage vs Price Plot
- Actual vs Predicted Plot
- Model Comparison Plot
- Feature Importance Plot
- Trained Machine Learning Model

---

## Project Structure

```text
vehicle-price-prediction-ml/
│
├── vehicle_price_prediction.py
├── dataset.csv
├── price_distribution.png
├── mileage_vs_price.png
├── actual_vs_predicted.png
├── model_comparison_rmse.png
├── feature_importance.png
├── requirements.txt
└── README.md
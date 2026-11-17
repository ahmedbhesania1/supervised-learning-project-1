# Predictive Insight Engine - House Price Prediction

Supervised Learning project: predicting house prices using regression models, built step by step as a learning journey.

## Project Structure

- `project_1.ipynb` - main Jupyter notebook with all the code and explanations
- `RealEstate_HousePrice_Dataset_4200.csv` - dataset (4200 houses)
- `PR. 1.pdf` - project problem statement
- `screenshots/` - output screenshots of the notebook

## What is inside the notebook

| Part | What was done |
|---|---|
| Part A | Theory: supervised learning, regression vs classification, assumptions, bias-variance |
| Part B | Dataset understanding, visualization, train-test split (80/20) |
| Part C | Simple Linear Regression using `area_sqft`, regression line, assumption checks |
| Part D | Model evaluation: MSE, MAE, RMSE, R2, Adjusted R2 with interpretation |
| Part E | Multiple Linear Regression using all 10 features + comparison with simple LR |
| Part F | Polynomial Regression (degree 2) on a non-linear dataset, linear vs polynomial comparison |
| Part G | Gradient Descent explained + Batch GD, SGD and Mini-Batch GD implemented from scratch and compared |
| Part H | Bias-variance analysis across all models, overfitting and underfitting evidence |
| Part I | Final report: best model, business interpretation |

## Key Results

| Model | R2 Score | MAE |
|---|---|---|
| Simple Linear Regression (area only) | 0.56 | ~ Rs 63 lakh |
| Multiple Linear Regression (all features) | **0.92** | ~ Rs 26 lakh |
| Polynomial Regression (degree 2, non-linear data) | 0.93 | - |

- Best model: **Multiple Linear Regression** (low bias, low variance, train and test R2 almost equal)
- Batch GD converged to exactly the same intercept as sklearn (-11,63,519)
- Degree 1 polynomial = underfitting, degree 15 = overfitting, degree 2 = sweet spot

## How to Run

1. Open `project_1.ipynb` in Jupyter
2. Update the CSV file path in the second cell if needed
3. Restart & Run All

## Tools Used

- Python 3.13, pandas, numpy, matplotlib, seaborn, scikit-learn

## AUTHOR 
- KING AHMED

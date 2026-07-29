# house-price-prediction

## Project Overview

This project predicts house prices using Machine Learning regression models. Several regression algorithms were implemented and compared to evaluate their prediction performance.

## Dataset

The dataset contains information about residential properties, including:

- Area
- Number of Rooms
- Parking
- Warehouse
- Elevator
- Address

Target variables:

- Price
- Price (USD)

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Data Preprocessing

- Feature Selection
- Standard Scaling
- Train/Test Split (80% / 20%)

## Models

- Linear Regression
- Polynomial Regression (Degree = 3)
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metric

- R² Score

## Project Workflow

1. Load dataset
2. Data preprocessing
3. Feature scaling
4. Split training and testing data
5. Train multiple regression models
6. Compare model performance using R² Score

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature engineering
- XGBoost
- LightGBM

- ## Results

| Model | R² Score |
|--------|---------:|
| Multiple Linear Regression | 0.3297 |
| Polynomial Regression | 0.4338 |
| Decision Tree Regression | 0.7259 |
| Random Forest Regression | 0.7984 |

## Conclusion

Among the evaluated models, Random Forest Regression achieved the highest R² score (0.7984), making it the best-performing model for this dataset. Decision Tree Regression also showed strong performance, while Polynomial Regression and Multiple Linear Regression achieved lower prediction accuracy. These results suggest that ensemble tree-based methods are more effective for predicting house prices in this dataset.

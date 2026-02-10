# World Happiness Score Prediction

## Course
Predictive Analytics (Curtin University)

## Objective
Predict national happiness scores using socioeconomic indicators and compare multiple machine learning models.

## Dataset
World Happiness dataset (public dataset used for academic purposes).

## Models implemented
- K-Nearest Neighbours (KNN)
- Linear Regression
- Random Forest

## Features
- Happiness Score
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom
- Generosity
- Perceptions of corruption

## Methodology
- Data cleaning and preprocessing
- Feature scaling (for distance-based models)
- Train / validation split
- Hyperparameter tuning
- Model comparison using standard regression metrics

## Evaluation metrics
- Adjusted R²
- MSE on test data
- % Variance

## Results (summary)
- Random Forest had the lowest MSE (0.1610), meaning it made the most accurate predictions
- KNN was also very strong, especially with 11 variables
- Linear regression had the highest error, likely because it can't capture nonlinear relationships
- In summary, "Life Ladder" score can be predicted using combination of chosen features and the most efficient model to predict is Random Forest model. 
Furthermore, emotions do help explain happiness levels, especially in the context of subjective well-being measures like the Life Ladder score.
All of these models had better performance with positive emotions

## Repository structure
- notebooks/  – experiments and modelling notebooks
- assets/     – plots and figures

## How to run
Run with Rstudio

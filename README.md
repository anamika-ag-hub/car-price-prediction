# car-price-prediction

## Objective
To predict car prices using machine learning regression algorithms and compare their performance.

## Algorithms Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

## Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

## Best Model
Random Forest Regressor

### Performance Before Hyperparameter Tuning
- R² Score: 0.953457
- MSE: 3674318.22
- MAE: 1365.35

### Best Hyperparameters
- n_estimators = 200
- max_depth = 10
- min_samples_split = 2

### Performance After Hyperparameter Tuning
- R² Score: 0.955648
- MSE: 3501314.16
- MAE: 1333.30

## Conclusion
Hyperparameter tuning improved the Random Forest model performance. The tuned Random Forest Regressor achieved the highest prediction accuracy and was selected as the final model.

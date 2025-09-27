# wdis-_finall-11# Temperature Forecasting

Predicting 2-meter temperature (`contest-tmp2m-14d__tmp2m`) using meteorological and climate features with **XGBoost**, **Ridge Regression**, and **CatBoost**. Hyperparameters are optimized with **Optuna**.

---

## Project Structure

rain_data.csv # Training data
sample_solution.csv # Validation data
test_data.csv # Test data
train_model.py # Training & prediction script
predictions_XGB_Optuna.csv
predictions_RIDGE_Optuna.csv
predictions_CATBOOST_Optuna.csv
xgb_model.pkl
ridge_model.pkl
catboost_model.pk

Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- lightgbm
- catboost
- optuna
- joblib
- How to Run
- train_data.csv
sample_solution.csv
test_data.csv
All models are optimized with Optuna to minimize RMSE on the validation dataset.

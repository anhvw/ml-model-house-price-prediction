# House Price Prediction

This project builds a machine learning regression model to predict median house values in Californian districts based on the 1990 census data.

## Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn (Random Forest)
* **Data Manipulation:** pandas, NumPy

## Project Structure
* `house-price-prediction.ipynb`: The core notebook containing data exploration and model training.
* `.gitignore`: Ensures large datasets and private API keys are not uploaded to GitHub

## Dataset
[Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Key Learnings
Random Search vs. Grid Search: Demonstrated how RandomizedSearchCV can achieve highly comparable results to exhaustive Grid Search but in a fraction of the time.

Parallel Processing: Using n_jobs=-1 during cross-validation utilizes all CPU cores, acting as a massive time-saver for ensemble models like Random Forests.

## Relevant documentation
[Random Forest](https://www.ibm.com/think/topics/random-forest)

[RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html#sklearn.ensemble.RandomForestRegressor)
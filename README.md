# Heavy Equipment Selling Price Prediction

## Overview

The project was developed as part of the **Heavy Equipment Selling Price Prediction Challenge**.

The workflow includes:

* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Feature engineering
* Categorical encoding
* Missing-value handling
* Log transformation of the target
* Model training and comparison
* Hyperparameter tuning
* Model ensembling
* Submission generation

## Models Used

Three gradient-boosting regression models were trained:

* **CatBoost Regressor**
* **LightGBM Regressor**
* **XGBoost Regressor**

The models were evaluated using:

* RMSLE
* R² Score

The final predictions were generated using a weighted ensemble of the three models. The ensemble weights were optimized using **SLSQP optimization** to minimize validation RMSLE.

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* CatBoost
* LightGBM
* XGBoost
* SciPy
* Matplotlib
* Seaborn

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the notebook in Jupyter Notebook or Kaggle.
4. Update the dataset path if running outside Kaggle.
5. Run the notebook cells sequentially.

## Author

**Anurag Basak**

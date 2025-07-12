# ATM Cash Demand Forecasting

This project was completed as part of an internship under YBI Foundation.

## Project Overview 

This project predicts cash demand at ATM locations using Random Forest Regressor based on demographics, seasonality, and event data.

## Result 

The Random Forest Regressor was trained and evaluated on historical ATM demand data.
**Mean Absolute Percentage Error (MAPE)** on test set was found to be : 0.0038 or 0.38%

## Files Included

- `ATM Cash Demand Forecast for BankServe.csv` - Given Dataset

- `ATM_Cash_Demand_Forecast_for_BankServe.ipynb` – Main notebook

- `atm_demand_model.pkl` – Saved trained model

- `requirements.txt` – Required Python libraries





## Features Used

- ATM type
- Nearby population
- Income level
- Date \& season
- Event/holiday flags

## How to Run

```bash

pip install -r requirements.txt

```


Then open the notebook or script to run the model.


## Model


The trained Random Forest model is saved as `atm_demand_model.pkl` and can be reused without retraining.

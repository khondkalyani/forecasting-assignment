# End-to-End Time Series Forecasting System

## Objective
Forecast next 8 periods of sales for each state using historical sales data.

## Implemented Models
- XGBoost
- ARIMA/SARIMA
- Prophet
- LSTM

## Best Model
Prophet achieved the lowest validation MAE and was selected as the final forecasting model.

## Project Structure
- forecasting_project.ipynb
- api.py
- requirements.txt
- data/

## Run Instructions

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:
- forecasting_project.ipynb

Run API:

```bash
uvicorn api:app --reload
```

API docs:
http://127.0.0.1:8000/docs
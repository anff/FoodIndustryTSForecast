# FoodIndustryTSForecast
We performed the Time Series Analysis to forcast the stocks of the top 10 food stores, 
with the data obtained from the Yahoo website.
We used LSTM and other ML models. Set the measurement metrics (MSE, RMSE, MAE, R2) to compare 
the performance of the different models.
Obvious improvement over accuracy was observed for the LSTM model.


## Setup
Use python3 (version 3.9). Follow the steps below to set up your environment. 
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirement.txt
```

>> python3 main.py

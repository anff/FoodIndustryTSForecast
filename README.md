# FoodIndustryTSForecast
We performed the Time Series Analysis to forcast the stocks of the top 10 food stores, 
with the data obtained from the Yahoo website.
We used LSTM and other ML models. Set the measurement metrics (MSE, RMSE, MAE, R2) to compare 
the performance of the different models.
Obvious improvement over accuracy was observed for the LSTM model.


## Setup
Use python3 (version 3.9). Follow the steps below to set up your environment at the first time. 
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirement.txt
```
Every time when running this project, set up the virtual environment by running	`source .venv/bin/activate`.

To run this project, run `python3 main.py`.

To quit the virtual environment in the end, run	`deactivate`.	


## Content
- main.py: entry of the project
- process_data.py: preprocessing the data into structured table
- build_model.py: build the DL and ML models
- analyze.py: calculate the metrics to measure the performance of each model 
- opt.py: environmental configuration


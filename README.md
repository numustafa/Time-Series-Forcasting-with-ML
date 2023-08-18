TS forecasting using ML techniques with Python. This is a learning project and I got inspired by the work of [RobMulla](https://www.kaggle.com/code/robikscube/time-series-forecasting-with-machine-learning-yt/notebook). 

The ML algorithm of XGBoost is used to tackle this tabluar data. The data for "Hourly Energy Consumption" is available on [Kaggle](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption) and all files can be accessed there. 

The data consists of hourly energy consumption for different region, over a period of 10 years. The goal is to predict the energy consumption for the next 24 hours.

## About Data
PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.

The hourly power consumption data comes from PJM's website and are in megawatts (MW).

The regions have changed over the years so data may only appear for certain dates per region.

## Ideas for what to build:
- Split the last year into a test set- can you build a model to predict energy consumption?
- Find trends in energy consumption around hours of the day, holidays, or long term trends?
- Understand how daily trends change depending of the time of year. Summer trends are very different than winter trends.
- Can you predict energy consumption for the next 24 hours?
- Can you predict energy consumption for the next 7 days?
- Can you predict energy consumption for the next 30 days?
- Can you predict energy consumption for the next 365 days?
- Can you predict energy consumption for the next 10 years?

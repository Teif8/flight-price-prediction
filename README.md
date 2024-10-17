# flight-price-prediction

This project performs Exploratory Data Analysis (EDA) and feature engineering to predict flight prices using a dataset from Kaggle.

## Dataset
The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction).

## Features
- **Airline**: The airline company (6 categories).
- **Flight**: Flight code (categorical).
- **Source City**: City where the flight takes off (6 categories).
- **Departure Time**: Derived categorical feature, representing the time of departure.
- **Stops**: Number of stops between source and destination (3 categories).
- **Arrival Time**: Derived categorical feature, representing the time of arrival.
- **Destination City**: City where the flight will land (6 categories).
- **Class**: Seat class (Business or Economy).
- **Duration**: Total travel time between cities.
- **Price**: Target variable, storing flight ticket price.

## Requirements
- pandas
- numpy
- seaborn
- matplotlib

To install dependencies, use:
```bash
pip install -r requirements.txt

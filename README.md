# weather-forecasting

Time series forecasting project that predicts future daily average temperatures using historical weather data and the ARIMA model.

## Dataset

- Filename: weatherHistory.csv  
- Description: This dataset contains weather data with a timestamp and temperature values collected at regular intervals.  
- Target Variable: Temperature (°C)  
- Resampled to: Daily average temperature

## Tools and Libraries

- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- statsmodels (ARIMA)

## Project Structure

weather-forecasting  
- weatherHistory.csv  
- weather_forecasting.ipynb  
- README.md  
- requirements.txt  

## Process Overview

1. Parsed and indexed the dataset by date  
2. Resampled the data to daily average temperature  
3. Visualized trends using line plots, ACF, and PACF  
4. Split the dataset into training and testing sets  
5. Trained an ARIMA model  
6. Forecasted the next 30 days of temperature  
7. Evaluated predictions using Mean Squared Error (MSE)

## Evaluation Metric

- Mean Squared Error (MSE)

Example output:

# Time-Series Forecasting Project--prophet-Sarimax
#### University project

# Time Series 

## Overview
This project focuses on time series forecasting using the SARIMAX and ETS (Error, Trend, Seasonality) models. The dataset used in this project contains historical data of wind farm parameters including active power, wind speed, wind direction, and ambient temperature. The goal is to predict future values of active power based on the provided features.

## Project Structure
The project is structured as follows:
- **Data Preparation**: The initial step involves data loading, preprocessing, and exploration to understand the dataset's characteristics. This includes handling missing values, converting date/time columns, and visualizing the data.
- **Modeling Approach**:
  - **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors)**: This model is implemented to capture the temporal dependencies and seasonality in the data. Parameters for the SARIMAX model are selected using cross-validation techniques.
  - **ETS (Exponential Smoothing)**: Another forecasting method, ETS, is employed to capture the trend and seasonality in the time series data.
- **Evaluation**: Model performance is evaluated using evaluation metrics such as Root Mean Squared Error (RMSE) and visual inspection of predicted vs. actual values.
- **Results**: The forecasted values are generated and stored in CSV format for further analysis or deployment.

## Dependencies
- Python 3.x
- Required Python packages: `statsmodels`, `pandas`, `matplotlib`, `scikit-learn`, `tqdm`

## Usage
1. Clone the repository:
2. Navigate to the project directory:
3. Install dependencies: pip install -r requirements.txt


## Files Included
- **timeseries_project.csv**: The dataset used for modeling and forecasting.
- **requirements.txt**: File containing the required Python packages.

## Results
- **forecast_results.csv**: Contains the forecasted values of active power for a specified period.

## Future Improvements
- Explore additional models such as Prophet or LSTM networks for comparison.
- Fine-tune model parameters for improved accuracy.
- Incorporate feature engineering techniques to enhance model performance.



## Acknowledgments
- Acknowledge any third-party libraries or resources used in the project.





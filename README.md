![download](https://github.com/dacenish/Gold-Price-ForecastingTSA/assets/82972335/0cba6eeb-f66a-4c12-87e5-36cdeccf37ef)

# Gold Price Forecasting using Exponential Smoothing

## Project Overview

This project demonstrates the implementation of a Gold Price forecasting model using Exponential Smoothing (ETS). The code showcases various steps involved in time series forecasting, including data preprocessing, model fitting, evaluation, and visualization.

## Project Structure

The project code is organized into several main sections:

### 1. Data Loading and Preprocessing

- Mounting Google Drive to access the dataset (assumes the dataset is stored in Google Drive).
- Loading a CSV file containing historical Gold Price data.
- Preprocessing the data by creating a datetime index and removing unnecessary columns.

### 2. Exploratory Data Analysis (EDA)

- Visualizing the monthly Gold Price data.
- Calculating summary statistics and visualizing yearly trends.

### 3. Naive Forecasting

- Implementing the Naive forecasting method.
- Visualizing the Naive forecasts and comparing them with actual data.

### 4. Exponential Smoothing (ETS) Model

- Creating and fitting an ETS model to the Gold Price data.
- Calculating the Mean Absolute Percentage Error (MAPE) to evaluate the model's accuracy.

### 5. Forecasting and Confidence Intervals

- Generating Gold Price forecasts for the testing period.
- Calculating lower and upper confidence intervals for the forecasts.

### 6. Visualization of Results

- Creating a comprehensive plot that includes actual values, forecasts, and confidence intervals.

## Dependencies

- NumPy
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Ensure you have a CSV file containing Gold Price data and update the file path in the code accordingly.
4. Execute the Python script, following the code comments and sections.

## Results

The project provides insights into Gold Price forecasting using both Naive and Exponential Smoothing methods. It calculates and visualizes the accuracy of the forecasts, allowing you to assess the performance of the chosen model.

## Acknowledgments

This project is for educational purposes and serves as a template for time series forecasting using Exponential Smoothing. Feel free to adapt the code for other forecasting tasks or use different models and methods.

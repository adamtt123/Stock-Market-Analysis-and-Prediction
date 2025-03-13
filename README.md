Stock Market Analysis and Prediction

This project focuses on analyzing and predicting stock market trends using machine learning models. The dataset is retrieved from Yahoo Finance, covering stock prices from January 1, 2023, to December 31, 2023. The analysis includes data preprocessing, visualization, and the application of regression models to predict stock prices.

Table of Contents

Installation

Dataset

Project Overview

Machine Learning Models

Usage

Results

Contributors

Installation

To run this project, install the necessary dependencies using the following command:

pip install pandas numpy matplotlib yfinance scikit-learn statsmodels

Dataset

The stock market data is retrieved from Yahoo Finance. The dataset includes:

Date: Trading date

Open: Opening price

High: Highest price of the day

Low: Lowest price of the day

Close: Closing price

Volume: Number of shares traded

Project Overview

The project follows these steps:

Data Retrieval: Fetch stock data using yfinance.

Data Preprocessing: Clean and structure the data.

Exploratory Data Analysis (EDA): Generate visualizations for insights.

Feature Engineering: Create relevant features for prediction models.

Model Training: Train multiple regression models to predict stock prices.

Evaluation: Assess model performance using error metrics.

Machine Learning Models

The following models are used:

Linear Regression

Ridge Regression

Lasso Regression

Logistic Regression (if applicable for classification tasks)

Usage

To execute the notebook:

Open Jupyter Notebook or Google Colab.

Run all cells in Project_1_Adam_Tereq.ipynb.

Visualize the results and model performance.

Example code snippet to retrieve stock data:

import yfinance as yf
market_data = yf.download('AAPL', start='2023-01-01', end='2023-12-31')
market_data.head()

Results

Stock price trend analysis

Model performance comparison

Feature importance analysis

Contributors

Adam Tereq

Feel free to contribute to the project or report any issues!

License

This project is licensed under the MIT License.

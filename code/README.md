# Financial ETL and Decision Tree Analysis

## Project Overview

This project focuses on extracting, transforming, and loading (ETL) financial data from Yahoo Finance, followed by predictive analytics using decision tree models. The project is divided into two main parts: the ETL process and the application of decision trees for both classification and regression tasks.

## Repository Structure

- **01_Data_ETL_and_Analysis.ipynb**: Handles the ETL process and applies a decision tree classifier for predicting stock price movement.
  
- **02_Decision_Tree_Analysis.ipynb**: Focuses on short-term predictive analytics using a decision tree regressor to forecast future stock prices.

## Notebook Details

### 01_Data_ETL_and_Analysis.ipynb

- **Data Extraction**:
  - Extracts historical stock data using the `yfinance` API.
  - Covers 5 years of daily stock prices for multiple tickers.

- **Data Transformation**:
  - Cleans and formats the extracted data for database storage.
  - Handles API rate limits to ensure sustainable data collection.

- **Data Loading**:
  - Stores data in MongoDB for initial storage, then transfers it to PostgreSQL for structured analysis.

- **Decision Tree Classifier**:
  - Trains a decision tree classifier to predict whether the stock price will rise or fall the next day.
  - Evaluates the model's accuracy, providing insights into prediction reliability.

### 02_Decision_Tree_Analysis.ipynb

- **Data Retrieval**:
  - Queries the most recent 30 days of stock data from PostgreSQL.
  - Prepares data for regression analysis.

- **Decision Tree Regressor**:
  - Trains a decision tree regressor to predict future stock prices.
  - Visualizes predicted prices alongside historical data for comparison.

- **Flask Integration**:
  - Sets up a Flask web interface allowing users to input tickers and view predictions interactively.
  - Provides interactive plots using Plotly for an engaging analysis experience.

## How to Use

1. **Run the Notebooks**: 
   - Start with `01_Data_ETL_and_Analysis.ipynb` to perform the ETL process and apply the decision tree classifier.
   - Then, use `02_Decision_Tree_Analysis.ipynb` to apply regression models for short-term price predictions and explore results through the Flask interface.

2. **Explore the Visualizations**:
   - Both notebooks include visualizations to help understand the data trends and the performance of the predictive models.

3. **Extend the Analysis**:
   - Adapt the code and methodologies to other financial datasets or prediction tasks.

## Dependencies

- Python 3.7 or higher
- Required Python packages:
  - `numpy`
  - `pandas`
  - `requests`
  - `pymongo`
  - `schedule`
  - `tqdm`
  - `psycopg2`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `scikit-learn`
  - `Flask`



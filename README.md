# Financial-ETL-and-Decision-Tree-Analysis

## Project Overview

This project focuses on extracting, transforming, and loading (ETL) financial data from Yahoo Finance, followed by predictive analytics using decision tree models. The project is divided into two main parts: the ETL process and the application of decision trees for both classification and regression tasks.

## Repository Structure

- **01_Data_ETL_and_Analysis.ipynb**: This notebook handles the ETL process of financial data from Yahoo Finance, storing it in MongoDB and PostgreSQL. It also applies a decision tree classifier to predict the direction of stock price movements.
  
- **02_Decision_Tree_Analysis.ipynb**: This notebook focuses on short-term predictive analytics using a decision tree regressor to forecast future stock prices based on the most recent data.

## Key Features

### 1. Data Extraction, Transformation, and Loading (ETL)
- **Data Extraction**: Real-time financial data is pulled from Yahoo Finance using the `yfinance` API.
- **Data Transformation**: The data is cleaned, processed, and formatted for further analysis.
- **Data Loading**: Processed data is stored in MongoDB for initial storage and later transferred to PostgreSQL for structured analysis.

### 2. Predictive Analytics with Decision Trees
- **Classification**: The first notebook uses a decision tree classifier to predict whether the stock price will rise or fall.
- **Regression**: The second notebook uses a decision tree regressor to forecast the exact future stock prices, providing a detailed prediction of market trends.

## How to Use

1. **Run the Notebooks**: Start with `01_Data_ETL_and_Analysis.ipynb` to perform the ETL process and initial classification analysis. Then, use `02_Decision_Tree_Analysis.ipynb` to apply regression models for short-term price predictions.
   
2. **Explore the Visualizations**: Both notebooks include visualizations to help understand the data trends and the performance of the predictive models.

3. **Extend the Analysis**: You can adapt the code and methodologies to other financial datasets or prediction tasks.

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

## Summary

This project provides a comprehensive approach to financial data analysis, combining the power of ETL processes with the predictive capabilities of decision trees. It serves as a valuable tool for financial analysts and data scientists interested in market trend predictions and decision-making support.

## License

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

- Haoran Yang
- Nan Nan
- Siyuan Song
- Chong Peng
- Zehao Zhou

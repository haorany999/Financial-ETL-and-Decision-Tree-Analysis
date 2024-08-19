## Web Interface Templates

This project includes a simple web interface built with Flask, allowing users to interact with the predictive models by inputting stock tickers and viewing the results. The web interface is composed of two main HTML templates:

### 1. home.html

- **Purpose**: This is the landing page of the web interface. It allows users to input a stock ticker symbol and submit it to view the corresponding analysis and predictions.
- **Functionality**:
  - **Form Input**: Users can enter a stock ticker (e.g., AAPL for Apple Inc.) into a text field.
  - **Submit Button**: Once a ticker is entered, users can submit the form to request the analysis, which is then processed by the Flask application.

### 2. results.html

- **Purpose**: This template displays the results of the analysis after a user submits a stock ticker.
- **Functionality**:
  - **Predicted Data Visualization**: Displays visualizations of the predicted stock price trends alongside historical data.
  - **Summary Metrics**: Shows key metrics such as the maximum, minimum, and average prices over the analyzed period.
  - **Interactive Elements**: Allows users to return to the home page or input another ticker for analysis.

### How to Use

- **Running the Web Interface**: The web interface is launched as part of the Flask application defined in the `02_Decision_Tree_Analysis.ipynb` notebook. Once the Flask app is running, you can interact with these templates via your web browser.
- **Customization**: Both templates are customizable. You can modify the HTML and CSS to better match your specific design preferences or add additional features.

These templates provide a simple and intuitive way for users to interact with the decision tree models developed in this project, making the analysis accessible through a user-friendly web interface.

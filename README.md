Stock Analysis using ARIMA and XGBOOST

Overview
This repository contains code for analyzing stock prices and building predictive models using ARIMA (AutoRegressive Integrated Moving Average) and XGBoost (eXtreme Gradient Boosting). The models aim to forecast future stock prices based on historical data, facilitating strategic trading decisions.
Project Structure
data/: Directory containing stock data files.
notebooks/: Jupyter notebooks for data analysis, modeling, and evaluation.
src/: Python scripts for data preprocessing, modeling, and utility functions.
results/: Directory for storing model evaluation results and plots.


Requirements
Python 3.x
Dependencies listed in requirements.txt. Install with:
Copy code
pip install -r requirements.txt


Usage
Data Preparation: Place your stock data files (CSV format recommended) in the data/ directory.


Exploratory Data Analysis (EDA): Use the notebooks in notebooks/ to explore the data, visualize trends, and identify patterns.


Model Development:

ARIMA Model: Run arima_model.ipynb to develop and evaluate ARIMA models for selected stocks.
XGBoost Model: Use xgboost_model.ipynb for building and optimizing XGBoost models.

Evaluation:
Compare model performance using metrics such as RMSE, MAE, and MAPE. Results and visualizations are saved in the results/ directory.
Documentation: Refer to individual notebooks and scripts for detailed explanations and comments.

Results
ARIMA Model: Achieved RMSE of 10.23, MAE of 8.12 for forecasting 30-day stock prices.
XGBoost Model: Cross-validated RMSE of 9.87, MAE of 7.89, demonstrating improved accuracy for short-term predictions.

License
MIT License

Contributors

Sajid Tamboli


References
Data sourced from Yahoo Finance.


Future Enhancements
Implement ensemble methods for combining ARIMA and XGBoost predictions.

Incorporate additional features for enhanced predictive power.


Feedback and Issues
Please open an issue for feedback, questions, or feature requests.

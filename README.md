# Suppliers Dashboard

Table of Contents
Overview
Features
Installation
Power BI Dashboard
Machine Learning Algorithms
ServiceType Classification
EuroCost Time Series Forecasting
Usage
Contributing
License
📚 Overview
This repository contains:

Power BI Dashboard: A dashboard that visualizes key metrics such as EuroCost, ServiceType usage trends, and institutional preferences using Power BI.
Machine Learning Models:
Classification: Predict the ServiceType using features like SupplierID, OIPID, InstitutionName, and Country.
Time Series Forecasting: Forecast EuroCost trends using models like ARIMA and Exponential Smoothing.
🚀 Features
Power BI Dashboard:

Visualizes trends in service usage across different institutions and suppliers.
Provides insights into historical EuroCost data.
Interactive dropdowns for filtering by specific vendors and service types.
Machine Learning Models:

Classification Model: Predicts the type of service used by an institution or supplier.
Time Series Forecasting: Forecasts future costs based on historical EuroCost data.
🛠 Installation
Prerequisites:
Power BI for running and modifying the dashboard.
Python 3.x for running machine learning models.
Required Python packages (can be installed via requirements.txt):
bash
Copy code
pip install -r requirements.txt
Steps:
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Power BI Dashboard:

Open the Power BI .pbix file using Power BI Desktop to explore the dashboard.
Ensure that you have access to the necessary data files.
Run the ML Models:

The machine learning models can be found in the ml_models/ directory.
Run the individual scripts to perform classification or time series forecasting:
bash
Copy code
python ml_models/service_type_classification.py
python ml_models/eurocost_forecasting.py

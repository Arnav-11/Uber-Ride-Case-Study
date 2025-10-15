# Uber-Ride-Case-Study
This project presents a comprehensive analysis of over 150,000 Uber ride bookings in the National Capital Region (NCR). The primary goal is to uncover patterns in ride-hailing data and build a machine learning model to predict whether a booking will be successfully completed.

The analysis is divided into three main parts:
1.  **Exploratory Data Analysis (EDA)**: To visualize and understand trends in booking times, locations, vehicle types, and payment preferences.
2.  **Time Series Analysis (TSA)**: To forecast the daily demand for Uber rides based on historical data.
3.  **Machine Learning (ML)**: To build and evaluate predictive models for ride completion status.

---

## Key Features

* **In-depth EDA**: Visual analysis of booking statuses, peak hours, popular routes, and user preferences.
* **Time Series Forecasting**: Utilizes the SARIMAX model to predict future ride demand, helping in resource allocation.
* **Predictive Modeling**: Implements Logistic Regression, XGBoost, and CatBoost to predict the likelihood of a ride being completed.
* **Comprehensive Reporting**: Includes detailed Jupyter notebooks for each stage of the analysis and a summary report.

---

## Key Insights from the Analysis

* **Booking Success Rate**: Approximately 55% of all ride requests are successfully completed. [cite_start]A significant 35% of bookings fail due to "No Driver Found," indicating a potential gap between demand and driver availability. [cite: 1]
* **Peak Demand Hours**: The busiest period for Uber bookings is the evening rush hour, from **6:00 PM to 7:00 PM**. [cite: 1]
* **Popular Locations**:
    * **Top Pickup Hotspots**: Karol Bagh, Nehru Place, and Palam Vihar. [cite: 1]
    * **Top Drop-off Destinations**: Vishwavidyalaya, Aya Nagar, and Jhilmil. [cite: 1]
* **Vehicle & Payment Preferences**:
    * The **Go Sedan** is the most popular vehicle choice, followed by Auto and Go Mini. [cite: 1]
    * **UPI** is the most preferred payment method, accounting for over 40% of transactions. [cite: 1]

---

## Technologies Used

* **Programming Language**: Python
* **Libraries**:
    * Pandas for data manipulation and analysis.
    * Matplotlib & Seaborn for static visualizations.
    * Plotly Express for interactive visualizations.
    * Statsmodels for time series analysis (seasonal decomposition, SARIMAX).
    * Scikit-learn for machine learning (Logistic Regression, pipeline creation, metrics).
    * XGBoost for gradient boosting model.
    * CatBoost for gradient boosting model.

---

## File Descriptions

* `uber.docx` / `Uber updt.pdf`: A detailed report summarizing the project's findings and analysis.
* `Uber EDA_Gemini.ipynb`: Jupyter notebook containing the Exploratory Data Analysis.
* `UberTSA.ipynb`: Jupyter notebook for the Time Series Analysis and demand forecasting.
* `Uber_ML.ipynb`: Jupyter notebook that covers the machine learning model development and evaluation for predicting ride completion.
* `dataset.csv`: The raw dataset containing over 150,000 Uber ride booking records.

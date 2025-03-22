# Supply-Chain-Forecasting-Enhancing-Operational-Efficiency-through-Data-Analytics

1. **Introduction**

**Problem Statement:**

Managing inventory efficiently is a critical challenge for businesses, as improper stock levels can lead to stockouts, excess inventory, and high operational costs.
Effective demand forecasting is essential to maintaining the right inventory balance, reducing waste, and optimizing supply chain operations. 

The objective of this project is to develop a forecasting solution that predicts future inventory requirements, enabling businesses to restock efficiently while minimizing costs.

**Objectives:**

Design an inventory forecasting model that leverages historical sales data to predict future demand, optimize reorder points, and calculate safety stock levels.

Improve decision-making by providing actionable insights, reducing operational inefficiencies, and streamlining inventory management.

**2. Methodology**

This project was conducted as part of my Operations Analytics coursework, where we explored the intersection of data science and supply chain optimization. We applied data engineering techniques and machine learning methodologies to build an inventory forecasting system.

**Tools and Technologies:**

Python: Used for data analysis, preprocessing, and model development.

MySQL: Served as the database for storing historical inventory and sales data.

ARIMA: A time-series forecasting model used for demand prediction.

Pandas/NumPy: Used for data manipulation and transformation.

Jupyter Notebooks: Used for coding, experimentation, and documentation.

**Data Sources:**

Inventory and sales data were extracted from a MySQL database, containing product-wise transaction records over multiple time periods.

**Approach:**

ETL Pipeline: Extracted, cleaned, and transformed raw inventory and sales data for forecasting.

**Exploratory Data Analysis (EDA):**

 Identified trends, seasonality, and demand patterns to inform model selection.

**ARIMA Forecasting:** 

Trained the ARIMA model to generate inventory demand forecasts with optimized parameters.

**Optimization Techniques:**

 Calculated reorder points, safety stock, and economic order quantity (EOQ) to refine inventory management.

**Results & Observations**

**Key Features:**

Demand Forecasting: Predicted future inventory levels using ARIMA, identifying Reorder Points (ROP), Safety Stock, and Economic Order Quantity (EOQ).

Inventory Optimization: Classified products based on forecasted demand, helping businesses adjust stock levels efficiently.

**Unexpected Findings:**

Products with irregular demand patterns required alternative forecasting techniques.

Seasonality challenges in demand patterns led to experimenting with seasonal models like SARIMA.

Data quality issues, including missing values and outliers, impacted initial model accuracy and required additional preprocessing.



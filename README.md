## Walmart Sales Forecasting: Data Analysis & Time Series Case Study

### Overview
This project is a comprehensive, real-world case study in sales analytics and forecasting for Walmart’s retail stores.
It covers the full data science pipeline—from data wrangling and exploratory analysis to feature engineering, segmentation, machine learning, and time series forecasting (Random Forest, ARIMA/SARIMAX).

The goal is to extract actionable insights for business decision-making, understand sales drivers, and generate accurate weekly sales forecasts to support inventory and strategy planning.

### Data Access & Reproducibility
Data for this project was programmatically downloaded from [https://www.kaggle.com/code/accountstatus/walmart-data-analysis) using the `kaggle` Python API.
Automated web-based data retrieval ensures up-to-date datasets for ongoing analysis and enables reproducible, end-to-end analytics pipelines.

### Key Steps & Techniques
- **Data Cleaning & Enrichment:**  
    Handled missing values, outliers, and engineered features (rolling sales, holiday uplift, etc.).
- **Exploratory Data Analysis:**  
    Visualized trends, seasonality, store performance, and key sales patterns.
- **Segmentation & Insights:**  
    Ranked stores by average weekly sales, identified top & lowest performers, and analyzed holiday uplift.
- **Correlation & Feature Importance:**  
    Assessed drivers of weekly sales using correlation matrices and Random Forest feature importance.
- **Predictive Modeling:**  
    Built and compared models (Random Forest, ARIMA/SARIMAX) for store-level sales forecasting.
- **Model Evaluation:**  
    Used MAE/RMSE, both absolute and as % of average sales, for robust performance assessment.
- **Business-driven Recommendations:**  
    Provided executive summary, scenario analysis, and “what-if” insights for decision support.

### Notable Results
- **Forecasting Accuracy:**  
    Both Random Forest and ARIMA models achieved strong accuracy (MAE and RMSE ~3-4% of average sales), supporting their practical use for weekly demand forecasting.
- **Actionable Insights:**  
    Store-level segmentation and holiday uplift analysis revealed key performance drivers and opportunity areas.
- **Scenario Forecasting:**  
    Delivered a “next 4 weeks” forecast to demonstrate real-world demand planning capability.

  - [Walmart Sales Analysis (Python) - Jupyter Notebook](https://github.com/movet306/Walmart-Sales-Analysis/blob/main/Walmart%20Sales%20Forecasting%20(1).ipynb)


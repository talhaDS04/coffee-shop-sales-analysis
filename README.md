# Coffee Shop Sales Profitability & Forecast Analysis

This project analyzes a coffee shop's sales dataset to uncover profitability patterns, forecast future sales, and provide actionable recommendations to improve profit margins and reduce losses.

## 📂 Project Structure

output_Analysis/ # Contains charts, summaries, and CSV outputs from analysis
Coffee Shop Sales Profitability & Forecast Analysi.ipynb # Colab/Jupyter notebook with full workflow
coffee_shop_sales_cleaned.csv # Cleaned dataset used for analysis


## 🎯 Objectives
- Clean and prepare raw sales transaction data.
- Perform exploratory data analysis (EDA) to identify trends and patterns.
- Calculate profit and loss for each product and category.
- Identify high-margin products and loss-making items.
- Forecast future sales using ARIMA-based time series modeling.
- Provide actionable recommendations for profitability improvement.

## 🛠 Workflow
1. **Data Loading** – Load raw dataset from Excel into Python environment.
2. **Data Cleaning** – Handle missing values, standardize columns, merge date/time, compute `total_sales`.
3. **EDA** – Summarize key metrics, visualize sales by product/category/store.
4. **Profit & Loss Calculation** – Estimate cost, compute profit, and profit margins.
5. **Profit Margin Analysis** – Rank products by margin and total contribution.
6. **Loss-Making Product Identification** – List items with negative profit and analyze causes.
7. **Sales Trend & Time-Series Analysis** – Explore patterns and seasonality in sales.
8. **Forecasting** – Predict next 30 days of sales with ARIMA/SARIMAX.
9. **Regression Analysis** – Identify key factors influencing profitability.
10. **Recommendations** – Suggest pricing, marketing, and operational changes.

## 📊 Key Features
- Automatic profit calculation (configurable cost percentage).
- Time-series forecasting with daily granularity.
- High/low margin product detection.
- Visualizations for sales, profits, trends, and forecasts.
- Exported CSV summaries and PNG charts in `output_Analysis` folder.

## 🚀 Getting Started
### Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, statsmodels, pmdarima (optional), openpyxl


👨‍💻 Author
Muhammad Talha Younas
📧 talhayounas696@gmail.com
   git clone https://github.com/<your-username>/coffee-shop-sales-analysis.git
   cd coffee-shop-sales-analysis

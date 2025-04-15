# Ativeer_Sales_DataAnalysis

Ativeer_sales_DataAnalysis is a comprehensive data analysis and visualization project designed to uncover key business insights from historical sales data. Using Power BI, the project explores sales, revenue, expense, and profit trends across various states, sales channels, product categories, and time periods (Month & Year).

Tools & Technologies

Tools & Technologies
Python – Used for cleaning the raw Excel data and saving it as a CSV.

Prophet – Used to create time-series forecast models for future revenue predictions.

Power BI – For data modeling, KPI tracking, and dashboard creation.

DAX (Data Analysis Expressions) – Used to create calculated fields and YoY metrics.

Step 1: Data Cleaning
Performed in Python using pandas to remove missing values, format dates, and ensure clean data before import into Power BI.

✅ Step 2: Forecasting with Prophet
A time-series forecasting model was created in Python using Facebook Prophet:

Cleaned monthly revenue data was used.

Forecasted revenue for the next 6 months.

Results saved as a CSV and imported into Power BI for visualization.

Labeled data as "Actual" vs "Forecast" for clarity in the report.

✅ Step 3: Dashboard Visuals in Power BI
KPI Cards: Total Revenue, Total Profit, YoY Growth %

Line Chart: Monthly revenue trend over years

Bar Chart: Top-performing states and product categories

Pie Chart: Sales channel distribution

Forecast Chart: Revenue forecast over time (Actual vs Forecast line)

✅ Step 4: DAX Measures
Created DAX measures for:

YoY Growth %

Total Profit and Revenue Calculations

Forecast integration using merged actual + forecast data




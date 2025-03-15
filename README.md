# OASIS-
Exploratory Data Analysis (EDA) on Retail Sales Data

📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset to derive meaningful insights. The dataset contains transaction-level details, including customer demographics, product categories, purchase amounts, and timestamps.

The analysis includes:

Data Cleaning & Preparation

Time Series Analysis (Monthly & Daily Sales Trends)

Customer & Product Insights

Sales Distribution Analysis

Correlation & Pattern Discovery

Advanced Visualizations (Heatmaps, Treemaps, Boxplots, and Pie Charts)

📂 Dataset

The dataset consists of the following key columns:

Date: Transaction timestamp

Customer ID: Unique identifier for customers

Product Category: Type of product purchased

Quantity: Number of items purchased

Total Amount: Revenue generated from the purchase

Age & Gender: Demographics of the customer

📊 Key Visualizations & Insights

The analysis is powered by Matplotlib, Seaborn, and Plotly, offering both static and interactive visualizations.

🔹 Sales Trends Over Time

Line charts for daily and monthly sales trends to identify seasonal patterns.

Time Series Decomposition to extract trend, seasonality, and residual components.

🔹 Customer & Product Analytics

Product Category Distribution to understand the most popular product types.

Customer Purchase Behavior Analysis to identify high-value segments.

🔹 Correlation & Distribution

Heatmaps to visualize relationships between numerical features.

Sales Distribution Analysis using histograms and KDE plots.

🔹 Advanced Visualizations

Treemap for hierarchical visualization of sales by product category.

Scatter & Boxplots for quantity vs. sales relationship analysis.

Pie Charts for sales contribution breakdown by category.

⚡ Setup & Installation

To run this analysis, ensure you have the required Python libraries installed:

pip install pandas numpy matplotlib seaborn plotly statsmodels kaleido

Additionally, if you're using Jupyter Notebook, enable inline plotting:

%matplotlib inline

🚀 Running the Code

Execute the Python script (eda_retail_sales.py) using:

python eda_retail_sales.py

Or run the cells in a Jupyter Notebook for an interactive experience.

📌 Summary & Business Recommendations

Peak Sales Periods: Identify high-revenue months to optimize stock and marketing campaigns.

Customer Segmentation: Focus on high-spending customers to enhance personalized offers.

Product Performance: Invest more in top-performing categories and adjust inventory accordingly.

Regional Analysis: Optimize localized promotions based on geographical sales insights.

Demand Forecasting: Utilize time series trends for better inventory and supply chain planning.



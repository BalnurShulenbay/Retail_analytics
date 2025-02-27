# E-commerce Data Analysis Project

This repository contains an analysis of e-commerce transaction data, exploring customer behavior, sales patterns, and product popularity across different countries.

## Project Overview

This project analyzes a retail dataset containing transactions for a UK-based online retailer. The analysis includes:

- Data cleaning and preprocessing
- Sales analysis by customer and country
- Seasonal sales trends
- Top-selling products and their monthly performance

## Dataset

The dataset contains online retail transactions with the following fields:
- InvoiceNo: Invoice number
- StockCode: Product code
- Description: Product description
- Quantity: Quantity of items purchased
- InvoiceDate: Date and time of purchase
- UnitPrice: Price per unit
- CustomerID: Customer identifier
- Country: Country where the customer resides

## Key Findings

### Customer Analysis
- Identified top 5 customers by total sales and number of orders
- Customer 14646 appears to be the highest-value customer

### Geographic Analysis
- United Kingdom dominates sales, followed by Netherlands, EIRE, Germany, and France
- When excluding UK, significant international markets become more visible

### Seasonal Trends
- Sales show distinct seasonal patterns with peaks around September-November
- Lower sales volumes observed in the beginning of the year

### Product Analysis
- Tracked the top 5 selling products (StockCodes: 23084, 84826, 22197, 22086, 85099B)
- Products 84826 and 23084 show significant sales increases in November, suggesting seasonal popularity

## Code Structure

The notebook contains:
1. Data loading and initial exploration
2. Data cleaning (handling nulls, date formatting, etc.)
3. Basic analytics (adding sales column)
4. Visualizations for customer, country, and seasonal analysis
5. Product performance analysis including monthly trends

## Technologies Used

- Python 3
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- NumPy for numerical operations

## Visualizations

The project includes several visualizations:
- Bar charts for top customers and countries
- Line charts for sales seasonality
- Time series analysis for top product performance

## Future Work

Potential extensions to this analysis:
- Customer segmentation analysis
- Basket analysis to identify commonly purchased product combinations
- Predictive modeling for future sales forecasting
- Geographic heat maps for sales distribution

## Data Source
The dataset is available from the following source:
https://raw.githubusercontent.com/rajeevratan84/datascienceforbusiness/master/ecommerce_data.zip

## How to Run

1. Clone this repository
2. Ensure you have the required Python packages installed
3. Run the Jupyter notebook to see the analysis

```python
# Install required packages
pip install pandas numpy matplotlib seaborn

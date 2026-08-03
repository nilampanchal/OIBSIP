# Retail Sales Exploratory Data Analysis

## Oasis Infobyte — Data Analytics Level 1, Task 1

### Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset. The aim is to identify sales trends, customer demographics, product-category performance, and useful business insights.

### Dataset

The dataset contains 1,000 retail transactions with the following columns:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

### Tools and Technologies

- Python
- Google Colab
- pandas
- matplotlib
- seaborn

### Analysis Performed

- Data inspection and missing-value check
- Duplicate-row check
- Descriptive statistics
- Monthly and quarterly sales-trend analysis
- Customer age-group and gender analysis
- Product-category sales and revenue analysis
- Correlation heatmap
- Revenue analysis by customer age group and product category

### Key Insights

- Sales were highest in May 2023, and Quarter 4 generated the highest quarterly sales.
- Clothing had the highest quantity sold.
- Electronics generated the highest total revenue.
- Customers aged 46–55 were the largest customer group.
- Price per Unit had a strong positive correlation with Total Amount.
- The 26–35 age group generated the highest Clothing revenue.

### Business Recommendations

1. Increase inventory and marketing activities before high-sales periods, especially Q2 and Q4.
2. Maintain adequate Clothing inventory because it has the highest demand.
3. Promote high-value Electronics products to increase revenue.
4. Use age-based marketing: promote Clothing to customers aged 26–35 and Beauty/Electronics to customers aged 46–55.

### How to Run

1. Download or clone this repository.
2. Open `retail_sales_eda.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the retail sales CSV file or update the file path in the notebook.
4. Run all cells in order.

### Note

The dataset provides product categories rather than individual product names. Therefore, the product analysis is performed at the category level.
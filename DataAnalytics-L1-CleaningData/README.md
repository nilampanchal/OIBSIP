# Data Cleaning Project

## Oasis Infobyte — Data Analytics Level 1, Task 3

### Project Overview

This project focuses on cleaning a messy real-world retail dataset using Python and pandas. The aim was to identify data-quality issues and transform the dataset into a clean, reliable, and analysis-ready format.

### Dataset

The original dataset contains 3,000 retail records with the following columns:

- OrderID
- CustomerID
- ProductName
- Brand
- Raw_Weight
- Country
- OrderDate
- UnitPrice

### Tools and Technologies

- Python
- Google Colab
- pandas
- matplotlib
- seaborn

### Data Cleaning Steps

- Checked dataset structure, missing values, duplicates, and data types
- Removed 8 repeated OrderID records
- Replaced missing ProductName and Brand values with `Unknown`
- Converted inconsistent Raw_Weight text values into a numeric `weight_g` column
- Filled missing weight and unit-price values using the median
- Standardised country labels and text formatting
- Converted OrderDate to datetime format
- Converted OrderID and CustomerID to string data types
- Detected weight outliers using the IQR method
- Capped 251 extreme weight values at 350 grams

### Results

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Row Count | 3,000 | 2,992 |
| Total Missing Values | 1,328 | 0 |
| Repeated Order IDs | 8 | 0 |
| OrderDate Data Type | object | datetime64[ns] |
| CustomerID Data Type | int64 | string |
| Weight Format | Inconsistent text | Numeric grams |

### Output

The final cleaned dataset is saved as:

```text
cleaned_online_retail_data.csv
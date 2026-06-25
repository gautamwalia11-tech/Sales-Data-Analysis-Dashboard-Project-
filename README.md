# Sales Data Analysis Dashboard

## Overview

This project analyzes sales data using Python, Pandas, NumPy, and Matplotlib. The dashboard provides insights into product performance, regional sales distribution, monthly sales trends, and top-selling products.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Dataset

The dataset contains the following columns:

* Date
* Product
* Region
* Sales
* Quantity

## Features

* Sales Per Product Analysis
* Sales Per Region Analysis
* Monthly Sales Trend Analysis
* Top Products Analysis
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)

## Sample Code

```python
import pandas as pd

df = pd.read_csv("Sales_Data.csv")
print(df.head())
```

```python
sales_by_product = df.groupby("Product")["Sales"].sum()
print(sales_by_product)
```

```python
sales_by_region = df.groupby("Region")["Sales"].sum()
print(sales_by_region)
```

## Dashboard Screenshots

### Sales Per Product

![Sales Per Product](images/sales_per_product.png)

### Sales Per Region

![Sales Per Region](images/sales_per_region.png)

### Monthly Sales Trend

![Monthly Sales Trend](images/monthly_sales_trend.png)

### Top Products Analysis

![Top Products](images/top_products.png)

## Key Insights

* Identified top-performing products based on total sales.
* Compared sales performance across different regions.
* Analyzed monthly sales trends and business growth patterns.
* Generated visual reports to support data-driven decision-making.

## Learning Outcomes

* Data Cleaning
* Data Analysis
* Exploratory Data Analysis (EDA)
* Data Visualization
* Dashboard Development
* Business Analytics

## Author

Gautam Walia

LinkedIn: [www.linkedin.com/in/gautam-walia1106](http://www.linkedin.com/in/gautam-walia1106)

GitHub: https://github.com/gautamwalia11-tech

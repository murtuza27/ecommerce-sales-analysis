# E-Commerce Sales ETL & Analytics Pipeline

## Project Overview

This project builds a Python-based e-commerce sales pipeline that processes monthly CSV files, validates data quality, combines valid records, generates business KPIs, and exports reporting datasets.

The pipeline includes schema validation, numeric validation, business-rule checks, error handling, PASS/FAIL pipeline logging, and automated reporting.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- OpenPyXL
- Jupyter Notebook

## Project Structure

```text
ecommerce-sales-analysis/
│
├── input/
│   ├── january_sales.csv
│   ├── february_sales.csv
│   └── march_sales.csv
│
├── test_data/
│   └── bad_sales.csv
│
├── output/
│   ├── combined_sales.csv
│   └── sales_pipeline_output.xlsx
│
├── ecommerce_sales_pipeline.ipynb
├── product_revenue_chart.png
├── monthly_revenue_trend.png
└── README.md

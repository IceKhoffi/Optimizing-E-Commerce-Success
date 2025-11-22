# Optimizing E-Commerce Success

### Project Overview

This project are use as project based learning in **ETL (Extract, Transform, Load)** methodology, aimed at unifying fragmented e-commerce data from multiple sources to deliver predictive business insights.

### Key Project Goals

This repository addresses the following business and data challenges:
1. **Data Unification**: Implement an ETL pipeline to combine raw data (Customer Info, Product Catalog, Sales Transactions) into a **single, clean, analytical fact table** (`ready_to_use_data`).
2. **Customer Segmentation**: Apply **RFM (Recency, Frequency, Monetary)** analysis to segment customers into clear, actionable value tiers (e.g., **Gold, Silver, Bronze**) for highly targeted marketing campaigns.

### Data & Methodology
* **Extract**: Data is sourced from multiple CSV files and Publicly available SQL database, simulating fragmented data silos.
* **Transform**:  Data cleaning, aggregation, merging, and feature engineering (specifically, calculating RFM metrics) are performed in the main Jupyter Notebook.
* **Load**: The transformed data is then loaded into csv that are ready to be used for analytics (`ready_to_use_data`).

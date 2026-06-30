# E-Commerce Customer Segmentation

## Overview
This project focuses on customer segmentation using the Online Retail II dataset. The objective is to understand customer purchasing behavior by applying data cleaning, exploratory data analysis (EDA), SQL analysis, and the RFM (Recency, Frequency, Monetary) framework.

By transforming raw transactional data into meaningful customer insights, this project demonstrates a complete data analysis workflow — from data preprocessing to business-oriented analysis.

## Dataset
- **Source:** [Kaggle – Online Retail II UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- **Description:**
  - UK-based online retail company
  - Transaction records from December 2009 to December 2011
  - Over 1 million transactions
  - Includes invoices, products, quantities, unit prices, customer IDs, countries, and transaction dates

> **Note:** Due to file size limitations, the dataset is not included in this repository. Please download it from the link above and place it in the `data/` directory before running the notebooks.

## Notebooks
### 1. EDA & Data Cleaning
Explore the dataset, identify data quality issues, clean invalid records, engineer new features, and prepare the data for customer segmentation.

### 2. RFM Analysis & Clustering (Coming Soon)
Build RFM features, segment customers based on purchasing behavior, and apply K-Means clustering to identify meaningful customer groups.

### 3. SQL Analysis (Coming Soon)
Use SQL to answer business questions related to customer behavior, sales performance, revenue, and product trends.

## Tools & Libraries
- **Python**
  - pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **SQL**
  - DuckDB

## Key Insights
- The dataset was reduced from 1,067,371 to 805,620 records after removing invalid and irrelevant transactions.
- Excluding the United Kingdom, Ireland generated the highest revenue, followed by the Netherlands and Germany.
- WORLD WAR 2 GLIDERS was the best-selling product, with more than 109,000 units sold.
- Sales consistently increased between September and December, with November recording the highest sales volume during the 2009–2011 period.

## Project Structure
```text
ecommerce-customer-segmentation/
│
├── data/
│   └── online_retail_II.csv
│
├── notebooks/
│   ├── EDA_and_cleaning.ipynb
│   ├── 02_RFM_and_Clustering.ipynb
│   └── 03_SQL_Analysis.ipynb
│
├── sql/
│   └── analysis.sql
│
├── images/
│   ├── monthly_sales.png
│   ├── revenue_by_country.png
│   └── top_products.png
│
├── README.md
└── requirements.txt
```

## Future Improvements
- Build customer segments using the RFM framework.
- Apply K-Means clustering for customer segmentation.
- Evaluate cluster quality using clustering metrics.
- Develop business recommendations for each customer segment.
- Create an interactive dashboard for data visualization.

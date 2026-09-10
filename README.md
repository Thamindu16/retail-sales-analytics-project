# Retail Sales & Customer Insights Dashboard

An end-to-end data analytics project analyzing ~1 million retail transactions to uncover sales trends and segment customers by purchasing behavior.

## Project Overview

This project follows the full data analyst workflow: cleaning raw transactional data, querying it with SQL, exploring it visually, applying customer segmentation (RFM analysis), and presenting the results in an interactive Power BI dashboard.

**Business questions answered:**
- What are the overall sales trends month by month?
- Which products and countries drive the most revenue?
- Who are our most valuable customers, and which customers are at risk of churning?

## Dataset

[Online Retail II](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci) — real transaction data from a UK-based online retailer (Dec 2009 – Dec 2011), ~1.07 million rows.

## Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn) — data cleaning and exploratory analysis
- **SQL** (SQLite) — querying and aggregating business metrics
- **Power BI** — interactive dashboard and visualization

## Process

### 1. Data Cleaning
Removed duplicate rows, handled missing Customer ID and Description fields, separated cancelled orders (returns), removed invalid prices, and converted data types. Reduced the dataset from 1,067,371 to 779,425 valid transaction rows.

### 2. SQL Analysis
Loaded the cleaned data into a SQL database and wrote queries to answer key business questions: total revenue and orders, top-selling products, monthly revenue trends, top customers by spend, sales by country, and repeat customer rate.

### 3. Exploratory Data Analysis & RFM Segmentation
Visualized sales trends and built an RFM (Recency, Frequency, Monetary) model to segment customers into groups such as Best Customers, Loyal Customers, Recent Customers, and At Risk / Lost customers.

### 4. Power BI Dashboard
Built a two-page interactive dashboard:
- **Sales Overview** — KPI cards (revenue, orders, average order value), monthly revenue trend, top 10 products, sales by country, with a country slicer for filtering.
- **Customer Insights** — customer segment breakdown, top spenders table, and a Recency vs Monetary scatter chart colored by segment and sized by purchase frequency.

## Key Findings

*(Fill this in with your own numbers once you review the dashboard — e.g. "Top 10 products accounted for X% of total quantity sold", "UK contributed X% of total revenue", "X% of customers are repeat buyers")*

## Dashboard Preview

*(Add a screenshot of each dashboard page here — drag and drop images directly into this file on GitHub, or upload them to the repo and reference them like this:)*

```markdown
![Sales Overview](images/dashboard_page1.png)
![Customer Insights](images/dashboard_page2.png)
```

## Files in This Repository

- `Retail_Analytics_Project.ipynb` — Python notebook covering data cleaning, SQL analysis, and RFM segmentation
- `Retail Sales Project.pbix` — Power BI dashboard file (download and open in Power BI Desktop to view)

## How to Run

1. Download the [Online Retail II dataset](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci) from Kaggle
2. Open `Retail_Analytics_Project.ipynb` in Google Colab or Jupyter
3. Follow the notebook cells in order (data loading → cleaning → SQL → EDA → RFM)
4. Open `Retail Sales Project.pbix` in Power BI Desktop to explore the dashboard

## Author

**H.M Thamindu Kavinda Dinujaya**
Data Science Undergraduate, Sri Lanka Technology Campus
[LinkedIn](https://www.linkedin.com/in/thamindu-kavinda) | [Portfolio](https://thamindu16.github.io/My-Portfolio/)

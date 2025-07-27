```markdown
# Sales Performance Dashboard

This repository features an interactive Excel dashboard designed to provide comprehensive insights into sales performance. It leverages detailed transactional and master data to visualize key metrics, trends, and performance against targets, facilitating data-driven decision-making.

---

## Dashboard Screenshots

Here you can place screenshots of your Excel dashboards to give a quick visual overview of the project.

### Dashboard Overview 1
![Dashboard 1 Screenshot](path/to/your/dashboard1_screenshot.png)

### Dashboard Overview 2
![Dashboard 2 Screenshot](path/to/your/dashboard2_screenshot.png)

### Dashboard Overview 3
![Dashboard 3 Screenshot](path/to/your/dashboard3_screenshot.png)

---

## Purpose

The primary goal of this dashboard is to monitor and analyze sales operations, identify performance drivers, highlight areas for improvement, and track progress against established targets. It serves as a single source of truth for stakeholders to quickly grasp the health of the sales business.

## Data Source

The dashboard is built upon five interconnected datasets (simulated as CSV files for this project, typically loaded into Excel for analysis):

* `sales_persons_table.csv`: Contains details of sales personnel and their assigned stores.
* `customers_table.csv`: Includes customer demographic information.
* `fact_table.csv`: The core transactional sales data, detailing quantities, order dates, and payment methods.
* `monthly_store_targets.csv`: Provides monthly sales targets for each store.
* `products_table.csv`: Contains product information, including categories, sales prices, and cost prices.

## Key Features and Insights

The dashboard is organized into several sections, each providing specific insights to various business questions:

### I. Executive Summary & Overall Performance

* [cite_start]**Total Revenue:** Clearly displays the overall sales revenue, which is **$5.4M**[cite: 1, 2, 3].
* [cite_start]**COGS (Cost of Goods Sold):** Shows the total cost associated with the goods sold, reported as **$3.1M**[cite: 1].
* [cite_start]**Profit:** Calculates the net profit from sales, amounting to **$2.3M**[cite: 1].
* [cite_start]**Profit Margin %:** Indicates the profitability percentage of sales, which is **42%**[cite: 1].
* [cite_start]**Products Sold:** Total number of distinct products sold: **100**[cite: 1].
* [cite_start]**Product Return Rate & Refund Rate:** Provides critical metrics for product performance and customer satisfaction, showing an **8.03%** return rate and an **8.05%** refund rate[cite: 1].
* [cite_start]**Quantity Returned:** Total quantity of items returned is **48,662**[cite: 3].

### II. Sales Trend & Profitability Analysis

* [cite_start]**Profit by Customer Age:** Visualizes profit distribution across different customer age groups (0-20, 21-30, 31-40, 41-50, 50+), allowing for targeted marketing strategies[cite: 1].
* [cite_start]**Profit by Gender:** Displays the profit generated from male vs. female customers, showing **$1M from Males and $1M from Females**[cite: 1].
* [cite_start]**Profit by Weekday:** Breaks down profit by the day of the week, helping identify peak selling days (e.g., **Monday** and **Tuesday** show the highest profit at **$343K** and **$332K** respectively, while **Friday** has the lowest at **$313K**)[cite: 1].
* **Month Over Month Sales & Returns Variance:** A line chart illustrating the percentage change in revenue month over month, along with the quantity returned. [cite_start]It helps track seasonality and performance fluctuations[cite: 15].
    * [cite_start]**August** and **May** had the highest revenue[cite: 5].
    * [cite_start]**February** and **July** had the lowest revenue[cite: 6].
    * [cite_start]Shows monthly variances like **+12.5% in August** and **-5.0% in July**[cite: 15].
* [cite_start]**Category Profit:** Ranks product categories by their profitability (e.g., **Water**, **Tea**, and **Sports Drink** are among the top categories)[cite: 1].
* [cite_start]**Top 5 Profitable Customers:** Identifies high-value customers based on their profit contribution (e.g., John Brown, Paul Noble, Laura Gross)[cite: 1].
* [cite_start]**Payment Method Breakdown:** Shows the distribution of sales across different payment methods (Cash, Credit Card, Debit Card, Online Payment)[cite: 1].

### III. Revenue vs. Target Performance

* [cite_start]**Total Revenue vs. Total Target:** A high-level comparison showing **Total Revenue of $5.4M** against a **Total Target of $5.3M**, with a positive **Variance of +3.7%**[cite: 2, 3].
* [cite_start]**Revenue vs Target by Month:** A detailed chart comparing actual monthly revenue against the target line, visualizing monthly performance against goals[cite: 15].
* [cite_start]**Weekday vs. Weekend Revenue:** Breaks down revenue contribution, showing **71% of revenue from Weekday sales** and **29% from Weekend sales**[cite: 2].
* [cite_start]**Day on Day Revenue:** Provides daily revenue figures and their percentage variance, allowing for granular tracking of daily sales fluctuations[cite: 2].
* [cite_start]**Quarter Revenue:** Summarizes total revenue for each quarter, indicating overall quarterly performance (e.g., **Q1: $1.3M**, **Q2: $1.6M**, **Q3: $1.4M**, **Q4: $1.4M**)[cite: 2].

### IV. Store Performance & Sales Person Analysis

* [cite_start]**Revenue VS Target by Store:** This critical section compares each store's `Total Revenue` against its `Target`, showing both the absolute `Variance` and `Variance %`[cite: 16].
    * [cite_start]**Top Performing Stores:** Stores like **Lee-Myers (+31.1%)**, **Lopez (+30.0%)**, and **Barron-Fleming (+29.5%)** significantly exceeded their targets[cite: 16].
    * **Underperforming Stores:** Identifies stores that consistently fell short of their targets. [cite_start]Specifically, **Martinez (-10.8%)**, **Berg-Trujillo (-12.4%)**, **Miller (-15.3%)**, and **Novak PLC (-24.6%)** are consistently underperforming, with **Novak PLC** being identified as the worst store[cite: 9, 10, 11, 12, 16].
* [cite_start]**Products Profit and Qty:** Lists products by their profit and quantity sold[cite: 3].
* [cite_start]**Sales Person Filter:** Allows for filtering the entire dashboard by individual `Sales Person` to analyze their specific performance[cite: 3].

## How to Use

The Excel file contains interactive elements (slicers for Store Name, Gender, Month Name, Sales Person Full Name) that allow users to dynamically filter the data and drill down into specific areas of interest.

## Technologies Used

* Microsoft Excel (for data loading, transformation, visualization, and dashboard creation)

## Future Enhancements

* Integration with live data sources for real-time updates.
* Addition of more advanced predictive analytics (e.g., sales forecasting).
* Further drill-down capabilities for customer segments and product analysis.
```

# Sales-End-to-End-Dashboard

1. Title
Sales End to End Dashboard

2. Short Description
This project addresses inconsistent revenue and profit performance by analyzing five years of historical sales data. The goal is to provide clear visibility into seasonal trends, top-performing products (SKUs), and channel profitability to optimize sales strategy. This Power BI dashboard consolidates complex, multi-source data into a live, interactive view, allowing business users to self-serve insights and make data-driven decisions.

3.Tech Stack
- Data Source: Multiple Excel Sheets 
- Data Cleaning & Initial EDA: Python (using Google Colab) 
- Data Modeling & Visualization: Microsoft Power BI 
- Data Processing: Power Query (M) and DAX for merging tables and creating calculated columns (e.g., profit, profit_margin_pct).

4. Features & Highlights
- Complex Data Modeling: Consolidated and merged six disparate tables (Sales, Products, Budgets, Customers, Regions, and States) that were initially unlinked.
- Feature Engineering: Created new key metrics, including profit and profit_margin_pct, to enable deeper profitability analysis.

5.Multi-Page Interactive Report: The dashboard is segmented into three key analysis pages:
1. Executive Overview & Trends:
- Displays high-level KPIs: $1.2bn Total Revenue, $461.8M Total Profit, 37.36% Profit Margin, 64K Total Orders, and $19.3K Revenue per Order.
- Visualizes seasonality ("Monthly Revenue Rhythm") and identifies key sales peaks (May-June) and lows (January).
- Includes an "Order Value Spectrum" to map customer spending tiers.
2. Product & Channel Performance:
- Identifies "Revenue Champions" (Top products by revenue, led by Product 26 & 25) and "High-Margin Heroes" (Top products by profitability).
- Provides a "Strategic Product Positioning" scatter plot (Revenue vs. Profitability) for portfolio analysis.
- Breaks down revenue, profit, and efficiency by sales channel (Wholesale, Distributor, Export).
3. Geographic & Customer Insights:
- Highlights geographic performance, showing California as the top state (19.5% of revenue) and the West as the top-performing region.
- Includes a "Total Profit by state" map for visual analysis.
- Segments customers to identify the "Top 5 Customers by Revenue" (led by Aibox Company and State Ltd).

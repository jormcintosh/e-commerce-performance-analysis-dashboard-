# e-commerce-performance-analysis-dashboard-

**Analysis Summary**

As a data analyst, I analyzed three months of fulfillment and sales data totaling 2,400 transactions for VivCalif, an e-commerce clothing business. I evaluated order activity, product performance, customer satisfaction, and delivery efficiency to uncover operational insights. Using Excel, data modeling, and DAX, I developed a dynamic dashboard that visualizes key performance indicators and supports leadership decision-making across product strategy, customer experience, and fulfillment operations

**Business Questions**

1) How many total orders did the business receive?

2) What products and categories drive the most revenue and quantity sold?

3) What is the overall customer satisfaction level (Avg. Rating)?

4) How efficient is the fulfillment process (Avg. Days to Deliver)?

5) What trends exist in sales, customer ratings, and delivery timelines?

 **Key Performance Indicators (KPIs)**

Total Orders: Total number of completed customer orders

Total Quantity: Total items sold across all orders

Total Amount: Total revenue generated

Average Rating: Mean product rating across reviews

Average Days to Deliver	Average delivery time (Delivery Date – Order Date)

**Key Insights & Recommendations**

**Sales Trends**

Peak Week: Week 10 with $64,915 in revenue and 1,128 units sold.
Lowest Week: Week 1 with $32,413 in revenue and 546 units sold.
Sales generally increase after Week 5, suggesting mid-quarter promotions or seasonal demand.


**Top Selling Products**

By Quantity:

T-Shirts (1,645 units)
Jeans (1,546)
Sneakers (1,186)
Tank Tops (912)
Bikinis (807)

By Revenue:

Sneakers ($127,637)
Jeans ($112,893)
Tank Tops ($57,394)
T-Shirts ($49,556)
Hoodies & Sweatshirts ($35,241)

**Customer Demographics**

Gender Split of VivCalif's buyers:

Female: 51.3%
Male: 40%
Unknown: 5.6%
Other: 3.1%


**Order Channel Preferences**

App dominates with $229K revenue (35% of total).
Website: $152K
Target.com: $118K
Partner App: $75K
Instagram: $73K


**Regional Performance**
Top 5 counties by revenue:

Los Angeles County: $215,551
San Diego County: $98,367
Sacramento County: $37,785
Santa Clara County: $37,449
Alameda County: $31,885


**Delivery & Customer Satisfaction**


Delivery Time:

Median: 2 days
75% of customers orders were delivered within 3 days
Max delay: 14 days 


Ratings:

5 stars: 721 orders
4 stars: 1,036 orders
3 stars: 495 orders
1–2 stars: 148 orders
→ 86% of ratings are 3 stars or higher, indicating good overall satisfaction.


🔍 Interesting Insights 

Sneakers are the biggest revenue driver despite not being the top in quantity → higher price point.
App orders dominate, suggesting strong mobile engagement. 
Los Angeles County alone accounts for ~33% of total revenue → huge regional concentration.
Delivery is generally fast, but there are outliers (14 days) which can account for the lower end customer ratings (may need further investigation).

1. Sales Performance

Order volume spikes during promotional periods and holidays. A small subset of products contributes the majority of revenue.

Recommendation: Increase visibility and stock levels of top performers.

2. Customer Sentiment

The overall average rating indicates strong customer satisfaction. However, specific product lines such as Pajama Sets (3.81), Tote Bags (3.85), Hoodies and Sweatshirts (3.86) are the lowest rated products.

Recommendation: Investigate customer complaints and consider quality improvements.

3. Operational Efficiency

Average delivery time is within an acceptable range, but there is variability by supplier region.

Recommendation: Review logistics partners and explore multi-warehouse distribution.

🛠️ Data Preparation & Cleaning

Standardized date fields and calculated delivery duration

Joined orders, products, and review tables

Removed duplicate rows and handled missing values

Created calculated columns (e.g., Revenue = Quantity × Unit Price)

Built DAX measures to power dashboard KPIs

Validated all fields for accuracy and consistency

📈 Dashboard Features

The dashboard includes:

KPI cards highlighting core business metrics

Sales trends over time

Top-selling products by quantity and revenue

Customer review distribution

Delivery efficiency by category or region

Interactive filters for deeper drill-through analysis

📉 Charts & Visuals
1. Total Orders Trend Chart

A line chart showing how total orders fluctuate over time. 
This helps identify seasonality, marketing impact, and demand cycles.

2. Total Quantity by Product or Category

A bar chart showing the total units sold across categories or SKUs.
Useful for inventory planning and identifying high-volume items.

3. Total Revenue (Total Amount) by Category

A bar/column chart visualizing which product categories drive the most revenue.
Supports financial planning and product strategy decisions.

4. Average Rating Distribution

A histogram or stacked bar chart showing the spread of customer ratings from 1–5 stars.
Reveals product satisfaction levels and quality concerns.

5. Average Days to Deliver by Category or Region

A bar chart or heatmap representing average delivery time broken down by category or shipping region.
Highlights logistical bottlenecks and performance inconsistencies.

6. Top 10 Best-Selling Products

A ranked bar chart showcasing the highest-performing items by quantity sold or revenue.
Helps stakeholders prioritize product placement, promotions, and stock capacity.

7. Delivery Time Trend Line

A time series line chart tracking how the company's average delivery speed changes over time.
Useful for monitoring operational improvements.

**Technologies Used**

Excel

DAX

Data modeling & ETL techniques

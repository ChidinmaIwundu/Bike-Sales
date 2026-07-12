**Bike Sales Analysis — 2024 Performance Dashboard**


Analyzing a year of bike sales data to identify which products, 
regions, and reps actually drive revenue and profit — built as an Excel dashboard with KPI cards, 
breakdown tables, and charts.



**Business Problem**

A bike retailer sold across 4 regions and 7 product lines throughout 2024, 
but had no consolidated view of performance. Leadership wanted answers to three questions: 
Which product categories are worth doubling down on? Which regions and reps are outperforming? Is there a seasonal pattern worth planning around?



**Dataset**

221 orders from Jan 2024 – Dec 2024
Fields: Order ID, Date, Region, Salesperson, Bike Model, Category, Units Sold, Unit Price, Total Revenue, Cost Per Unit, Total Cost, Profit
4 regions (East, North, South, West) · 5 salespeople · 7 bike models across 6 categories
No missing values or duplicates — used as-is



**Tools**

Excel (formulas: SUM, SUMIF; pivot-style summary tables; native charts)



**Approach**

Built KPI summary cards for total revenue, profit, units sold, and overall margin
Broke down revenue and profit by category, region, and salesperson using SUMIF
Added a monthly trend table to check for seasonality
Visualized each breakdown with a chart (3 bar charts + 1 line chart) on a single dashboard tab


**Key Findings**

Electric eBikes punch way above their weight. They generated $462,000 — 42.7% of total revenue — from only 210 units sold (17% of total units). Compare that to City category bikes, which sold the most units (324) but brought in only $179,400. Fewer, higher-value sales beat volume here.
Margin is flat at 40% across every category and model. Since margin doesn't differentiate performance, revenue mix (which products sell) is the real lever, not pricing or cost control.
South is the top-performing region at $320,930 in revenue, driven by having the most orders (60) rather than larger order sizes.
Eve Davis is the top-performing salesperson, generating $273,900 across 51 orders — about $42,500 more than the lowest performer despite a similar number of orders, suggesting a difference in what she's selling, not how much.
Revenue is seasonal, dipping to $47,880 in August (the lowest month) and peaking at $122,430 in July, with a second smaller peak in October ($119,020).

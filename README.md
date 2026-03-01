📊 Sales & Buyer Performance Dashboard – Power BI
🔍 Project Overview
Sales_-and_-Buyer_Performance is a Power BI dashboard project designed to analyze overall sales performance and evaluate buyer contribution across different product categories.
This project helps businesses:
Track revenue, cost, and profit
Measure buyer-wise performance
Analyze sales trends over time
Identify top-performing categories and buyers
Monitor profit margins and revenue growth
🎯 Business Objective
The goal of this project is to build an interactive dashboard that enables:
📈 Sales trend analysis (Monthly / Quarterly / Yearly)
🏆 Buyer performance ranking
💰 Profitability and margin tracking
📊 Revenue share and contribution analysis
🔎 Data-driven decision making
🗂 Data Model (Star Schema)
This project follows a Star Schema design for better performance and scalability.
📌 Fact Table
Sales
Date
Category
Units Sold
Sale Value
Cost Value
Profit (Calculated)
Profit %
📌 Dimension Table
Buyers
Buyer Name
Category
Clean Category (for relationship)
📌 Date Table (Optional)
Year
Month
Quarter
Day Type
YTD calculations
🔗 Relationships
Buyers[Clean Category] → Sales[Clean Category] (One-to-Many)
Date[Date] → Sales[Date]
📐 Calculated Columns
In Sales Table:
Clean Category
Clean Chain
Year
Month Name
Quarter
Profit
Profit %
Revenue Band
Units Band
In Buyers Table:
Clean Category (Trimmed & Uppercase)
📊 Key DAX Measures
Sales Metrics
Total Revenue
Total Cost
Total Units Sold
Total Profit
Profit Margin %
Revenue LY (Last Year)
Revenue Growth %
Revenue YTD
Buyer Metrics
Total Revenue Buyer
Total Profit Buyer
Buyer Revenue Rank
Buyer Revenue Share %
📈 Dashboard Features
KPI Cards (Revenue, Profit, Margin)
Monthly Revenue Trend (Line Chart)
Category-wise Sales (Bar Chart)
Buyer Ranking (Table / Matrix)
Revenue Share (Pie / Donut Chart)
Slicers for Year, Category, Buyer
🛠 Tools & Technologies Used
Power BI Desktop
DAX (Data Analysis Expressions)
Excel / CSV (Data Source)
Data Modeling (Star Schema)
🚀 How to Use
Download the .pbix file from the repository.
Open in Power BI Desktop.
Refresh data if required.
Use slicers to explore sales by category, buyer, and time.
Customize visuals or measures as needed.
📊 Key Insights Generated
Identified top revenue-generating buyers
Measured profitability by category
Analyzed seasonal sales trends
Evaluated revenue contribution %
Compared Year-over-Year growth
📂 Repository Structure
Copy code

Sales_-and_-Buyer_Performance/
│
├── Data/              → Raw dataset files
├── PowerBI/           → .pbix file
├── Images/            → Dashboard screenshots
└── README.md
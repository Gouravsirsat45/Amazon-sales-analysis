🛒 Amazon Sales Analytics: Power BI Dashboard
A dynamic and interactive dashboard built to replicate Amazon sales insights—tracking revenue performance, product reviews, and sales trends across categories and time.

🔍 Short Description / Purpose
The Amazon Sales Dashboard in Power BI provides a visual overview of key performance indicators like YTD/QTD sales, product reviews, and category insights. It helps stakeholders understand sales performance, customer sentiment, and top-performing products using time intelligence and DAX.

🛠 Tech Stack
The dashboard was developed using:

📊 Power BI Desktop – Core platform for data modeling and visual storytelling.

🔄 Power Query Editor – For transforming, cleaning, and preparing CSV data.

🧠 DAX (Data Analysis Expressions) – To build measures using YTD, QTD, and filter logic.

🧱 Data Modeling – Star schema design with relationships enabling cross-filtering.

📁 File Format – Developed in .pbix, sourced from a structured CSV dataset.

📂 Data Source
Source: Simulated Amazon sales CSV
The dataset includes product-level sales data with attributes like date, product category, number of reviews, quantity sold, and sales value. It’s structured to support temporal analysis (monthly, weekly, YTD, QTD) across various categories.

🌟 Features / Highlights
• Business Problem
E-commerce businesses like Amazon manage large volumes of transactional data. There’s a need for quick, insightful dashboards that summarize performance across time and product dimensions.

• Goal of the Dashboard
To build a Power BI dashboard that:

Highlights YTD and QTD performance

Identifies top-selling and top-reviewed products

Enables weekly and monthly trend analysis

Helps in understanding category-level performance through visuals

• Walkthrough of Key Visuals
🔹 KPI Cards (Top Panel)

YTD Sales: Track year-to-date revenue

QTD Sales: Understand quarterly performance shifts

YTD Products Sold: Monitor total product movement

YTD Reviews: Gauge customer feedback across products

📈 YTD Sales by Month (Line Chart)

Shows monthly sales trends

Identifies seasonal spikes and dips in revenue

📊 YTD Sales by Week (Column Chart)

Visualizes short-term weekly performance

Useful for campaign analysis or weekly review

🌡 Sales by Product Category (Heat Map/Text Chart)

Gives a macro-level view of category-wise performance

Highlights which product types are leading or lagging

🏆 Top 5 Products by YTD Sales (Bar Chart)

Identifies key revenue-generating products

Great for inventory planning or promotions

⭐ Top 5 Products by YTD Reviews (Bar Chart)

Captures customer favorites or most-discussed items

Helps in improving customer experience and marketing focus

🎓 What I Learned
Data Preparation: CSV import, Power Query transformation, null handling

Data Modeling: Relationship building, star schema design

DAX Functions:

TOTALYTD, TOTALQTD – For cumulative time-based measures

WEEKNUM, QUARTER – For custom date segmentation

CONCATENATE, CALCULATE, FILTER – For custom logic and expressions

Visual Techniques:

Custom sorting

Conditional formatting

Card visuals

Hierarchical filters and navigation

Time Intelligence: Built a Date Table to enable YTD/QTD calculations and support dynamic analysis

🖼️ Screenshots / Demos
![Dashboard Preview].(https://github.com/Gouravsirsat45/Amazon-sales-analysis/blob/main/Amazon%20sales%20dashboard.png)

Alt text examples:

“YTD Sales Line Chart showing steady growth through the year”

“Bar Chart of Top 5 Products by Reviews indicating strong customer engagement”


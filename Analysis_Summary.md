📊 Sales Data Analysis Using Python

Analyzed an apparel sales dataset to uncover key insights into revenue, customer behavior, cancellations, and seasonal demand trends.
Performed data cleaning, transformation, and exploratory data analysis (EDA) using Python (Pandas, NumPy, Matplotlib, Seaborn).
Identified top-performing categories (Set, Kurta), calculated AOV (₹545) and Cancellation Rate (14.3%), and visualized monthly sales patterns.
Findings highlighted seasonal peaks (April–May) and faster fulfillment via Amazon, providing actionable business insights.
This Python analysis also served as the data foundation for a Power BI storytelling dashboard to enhance business decision-making.

📊 Sales Data Analysis — Python Project Summary:

🧩 Project Overview

This project focuses on analyzing an apparel sales dataset to extract meaningful insights about revenue, order behavior, cancellations, and fulfillment performance.
The analysis was carried out entirely in Python, leveraging libraries for data cleaning, manipulation, and visualization.
The same dataset was later used to build a Power BI dashboard for storytelling and interactive reporting.

📘 Dataset Reference

📂 Source:
/kaggle/input/vijayarani-t-final-test1/sales_dataset.xlsx - Sheet1.csv

The dataset contains:

Order details (Order ID, Quantity, Amount, Status)

Product category, size, fulfillment type, and order type (B2B/B2C)

Date and shipping information

🧮 Analysis Objectives

Examine overall sales performance and revenue trends.

Identify top-performing product categories and seasonal demand patterns.

Calculate Average Order Value (AOV) and Cancellation Rate.

Evaluate fulfillment performance and shipping timelines.

Derive actionable insights for improving operational efficiency.

🧠 Techniques & Libraries Used
Process	Tools / Libraries
Data Cleaning & Processing	Pandas, NumPy
Statistical Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Environment	Jupyter Notebook (Kaggle)
🧾 Key Analytical Steps

Data Preparation

Imported dataset and standardized column names.

Removed nulls, duplicates, and invalid entries.

Normalized Status field to handle inconsistent labels (e.g., Cancelled, cancelled).

Derived a new column, New_Amount, to set the value = 0 for cancelled orders.

Feature Engineering

Created KPIs:

Total Sales

Total Orders

Average Order Value (AOV)

Cancellation Rate

Grouped and aggregated data for category-wise and monthly analysis.

Visualization & Insights

Line charts for monthly revenue trends.

Bar charts for category performance.

Pie charts for order status distribution.

Boxplots to detect outliers in sales amounts.

📈 Key Findings

Total Sales: ₹72 Million+

Average Order Value (AOV): ₹545

Cancellation Rate: ~14.3%

Top Categories: Set and Kurta dominated sales across all months.

Seasonality: Sales peaked during April–May, showing clear seasonal trends.

Fulfillment: Amazon channel maintained faster shipping timelines (1–2 days).

Customer Behavior: B2B orders, though fewer, had a higher average spend per order.

💡 Business Insights

Focus marketing efforts on Set and Kurta, which contribute the majority of revenue.

Reduce cancellation rates through fulfillment process improvements.

Utilize seasonal demand peaks (April–May) for stock optimization and targeted promotions.

Encourage B2B partnerships to capitalize on higher-value orders.

🚀 Next Steps

Extend analysis with predictive modeling for sales forecasting.

Automate KPI reporting using Python scripts or Power BI data pipelines.

Incorporate customer feedback and ratings for sentiment-based analysis.

✨ Project Outcome

This project demonstrates the power of Python in transforming raw sales data into actionable insights.
The findings formed the analytical base for a Power BI storytelling dashboard, bridging technical analysis and business strategy.

👩‍💻 Author
Vijayarani T

📧 Email: vijimusic11@gmail.com

🔗 GitHub: https://github.com/Vijayarani146/

🔗 Kaggle: https://www.kaggle.com/code/vijayaranit/final-project-vijayarani-t/

✅ “Data tells stories — Python helps reveal them.”

✅ “Turning raw data into visual insights through Python analytics.”

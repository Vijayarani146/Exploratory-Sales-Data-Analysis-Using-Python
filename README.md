# Exploratory-Sales-Data-Analysis-Using-Python
- Exploratory Data Analysis (EDA) of Sales Dataset Using Python. Performed data cleaning, transformation, and exploratory data analysis using Python (Pandas, NumPy, Matplotlib, Seaborn) to uncover sales trends, high-demand products, and seasonal patterns for better business decision-making.

🧩 **Exploratory Sales Data Analysis Using Python**

 - Uncovering sales trends, product performance, and customer behavior through data-driven insights.

📘**Project Overview**

 - This project focuses on analyzing a sales dataset (apparel/dress sales) to uncover key insights about revenue trends, product demand, cancellations, and seasonal variations.
 - Using Python for data cleaning, transformation, and exploratory data analysis (EDA), the goal was to convert raw sales data into actionable business intelligence.

🎯 **Objectives**

- Analyze overall sales performance and revenue distribution.

- Identify top-performing products and low-demand categories.

- Evaluate order cancellations and their impact on business.

- Understand seasonal demand patterns for better stock management.

- Derive insights to support strategic decision-making.

🛠️ **Tools & Technologies**

 - Category	Tools Used
 - Programming	Python
 - Libraries	Pandas, NumPy, Matplotlib, Seaborn
 - Environment	Jupyter Notebook / VS Code
 - Dataset	CSV-based Excel Dress Sales Dataset

🔍 **Key Analysis Performed**

 - Data cleaning and formatting (handling nulls, renaming columns, removing outliers).

 - Sales trend analysis (monthly, category-wise, product-wise).

 - Cancellation and return analysis to assess operational efficiency.

 - Average Order Value (AOV) and revenue distribution calculations.

 - Visualizations to identify seasonal patterns and high-demand categories.

📈 **Key Insights**

 - Set and Kurta were the top-performing categories, driving maximum revenue.

 - Cancellation Rate ~14%, highlighting fulfillment and quality issues.

 - April–May were peak sales months — inventory planning needed for these periods.

 - B2B customers showed a higher average spend per order compared to B2C.

 - Seasonal variation and demand trends suggest potential for targeted campaigns.

🧮 **Sample Python Code Snippets**

# Load and explore the dataset
import pandas as pd
df = pd.read_excel("/kaggle/input/vijayarani-t-final-test1/sales_dataset.xlsx - Sheet1.csv")
df.info()

# Clean and prepare data
df['Status'] = df['Status'].str.strip().str.lower()
df = df.dropna(subset=['Amount'])

# Calculate AOV
valid_orders = df[df['Status'] != 'cancelled']
aov = valid_orders['Amount'].sum() / valid_orders['Order ID'].nunique()
print(f"AOV: {aov:.2f}")

# Visualize sales trends
import matplotlib.pyplot as plt
df.groupby('Month')['Amount'].sum().plot(kind='line', marker='o', title='Monthly Sales Trend')
plt.show()

📊 **Results Summary**

 - KPI	Value	Description
 - Total Revenue	₹72M	Total valid sales after cancellations
 - Total Orders	120K+	Unique orders analyzed
 - Average Order Value (AOV)	₹545	Avg. customer spend per order
 - Cancellation Rate	14.29%	Percentage of cancelled orders
 - Peak Months: April–May	Highest demand period

🚀**Next Steps & Future Enhancements**

 - Automate insights extraction with Python dashboards (e.g., Streamlit).

 - Apply predictive modeling to forecast future sales.

 - Integrate product review and feedback data for sentiment-based insights.

 - Connect this analysis with the Power BI visualization project for storytelling dashboards.

🏁 **Conclusion**

This project demonstrates how Python-based data analytics can transform raw sales data into meaningful insights for decision-making.
It forms the analytical foundation for a Power BI dashboard, showcasing interactive storytelling and business impact visualization.

📬 Contact

Vijayarani T

📧 Email: vijimusic11@gmail.com

🌐 GitHub: https://github.com/Vijayarani146/

💼 LinkedIn: https://www.linkedin.com/in/vijayarani-t-432410296

✅ “Turning raw data into actionable insights through Python analytics.”

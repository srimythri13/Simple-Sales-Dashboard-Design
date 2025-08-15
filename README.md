# Simple-Sales-Dashboard-Design
This Power BI dashboard visualizes Superstore sales trends over time, helping to identify top-performing months, product categories, and regions. Interactive slicers allow quick filtering by category, region, and date for deeper insights.
# 📊 Superstore Sales Analysis – Power BI Dashboard
## 🗂 Dataset
- **Source:** Superstore Sales dataset
- **Key Columns:** Order Date, Sales, Category, Region, Segment, City, State

## 🔹 Steps Performed
1. Imported dataset into Power BI.
2. Created a **Month Year** column:
   ```DAX
   Month Year = FORMAT('Superstore_Sales'[Order Date], "MMM YYYY")
YearMonthNum = YEAR('Superstore_Sales'[Order Date]) * 100 + MONTH('Superstore_Sales'[Order Date])
Sorted Month Year by YearMonthNum.

# Built a Sales Trend Line Chart.
Added Slicers for Category, Region, and Order Date.
Applied visual formatting for better readability.

# 📈 Key Insights
November 2016 had the highest sales, mainly from Technology.
Office Supplies had more orders, but Technology generated more revenue per order.
West Region had consistently high sales.

# 🛠 Tools Used
Power BI
DAX for calculated columns


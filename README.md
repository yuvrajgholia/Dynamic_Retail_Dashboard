# Dynamic_Retail_Dashboard
# Overview:-
The Dynamic Retail Dashboard is a dynamic Excel-based tool to analyze and visualize retail data.Using Power Query, Pivot Tables, Slicers, Timelines, it helps identify top-selling categories, monitor profit margins, track returns, solves key business questions and support data-driven decisions across teams.
# Datasets Used:-
## 1.Orders Tables:-
The Orders table contains details of customer orders, including product, shipping, and financial metrics.

### Sample Data:-
<img width="1160" alt="image" src="https://github.com/user-attachments/assets/3ce78ff2-f107-45d9-95aa-3bb4c32e57ec" />


## 2.Returns Tables:-
Tracks orders that have been returned, along with the associated markets.

### Sample Data:-
<img width="396" alt="image" src="https://github.com/user-attachments/assets/6f41ca34-c875-4384-b51e-45fa96698608" />


## 3. People Table:-
Contains details about sales representatives and their respective regions.

### Sample Data:-
<img width="239" alt="image" src="https://github.com/user-attachments/assets/0ee51b1c-1f1c-475a-b82b-834980d176f1" />

# 🌐 Problem Statements & Steps:-

## 1. 🎯 Key Performance Indicators (KPIs):-

### Goal: Display Total Sales, Total Profit, Total Quantity, Orders, and Profit Margin
1. Imported data using Power Query.

2. Create calculated columns for:

   Profit Margin = Profit / Sales.

   Total Orders = Count of Order ID.

3. Use Excel formulas to calculate:

   Total Sales = =SUM(Sales).

   Total Profit = =SUM(Profit).

   Total Quantity = =SUM(Quantity).


4. Build a dynamic KPI table and use symbols to enhance visual appeal.
<img width="915" alt="image" src="https://github.com/user-attachments/assets/2f18657e-fbc3-46ff-859b-94c6cfa60668" />

Created calculated columns: Profit Margin = Profit / Sales

KPI values derived from Pivot Table calculations.

Custom KPI Table created using shapes, icons, and Excel formulas.

## 2. 📈 Sales and Profit Trend Analysis:-

### Goal: Identify monthly trends.

Pivot Table with Date grouped by Month/Year

Line chart plotted with slicers (Segment, Category, Region)

# 3. 📦 Category-Wise Profit:-

### Goal: Visualize profitability across categories.

Pivot Table with Category in rows and Profit in values

Sorted and visualized using bar chart

Added slicers for interactivity

# 4. 🌐 Segment-Wise Sales Share:-

### Goal: Show share (%) for each customer segment

Pivot Table with Sales by Segment

Calculated % contribution

Displayed via Donut Chart with dynamic labels

# 5. 📊 Sales by Country:-

### Goal: Highlight countries with highest sales

Pivot Table with Country and Sales

Used Conditional Formatting/Heatmap

# 6. 🔹 Top 5 Subcategories:-

### Goal: Identify best-performing sub-categories

Pivot Table with Sub-Category and Sales

Sorted and filtered top 5

Visualized via column chart

# 7. 🔻 Bottom 5 Subcategories:-

### Similar to above but with lowest sales

Displayed via column chart for quick identification

# 8. 📅 Yearly Sales Trend :-

Line chart showing year-wise performance

Timeline slicer added

# ⚙️ Dynamic Features:-

Power Query: For data import and transformation

Slicers/Timeline: Filter charts and tables in real-time

KPI Icons: Unichar function for symbols

Group Shapes: Consistent dashboard layout

# ✨ Additional Insights:-

Return Analysis: By market and product category

Product-Level Profitability: Most/least profitable SKUs

Segment/Region Comparisons: With KPIs per dimension

# 🌟 Project Significance:-

This dashboard enables Walmart stakeholders to:

Monitor sales and profit KPIs at a glance

Identify trends and performance gaps

Optimize marketing strategies and stock decisions

# 📸 Screenshots Included:-

KPI Panel

Sales by Country Heatmap

Top & Bottom Subcategories

Yearly Sales Line Chart


# 📚 Future Improvements:-

Add return rates by customer segment

Integrate forecasting using regression models

Add map visualization with Power BI or Excel Map Charts

																						
		 

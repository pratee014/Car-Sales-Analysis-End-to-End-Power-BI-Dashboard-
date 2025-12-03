
## 📌 **Project Overview**

This project demonstrates how to build a fully dynamic and interactive **Power BI dashboard** for analyzing car sales data. The dashboard highlights business performance using KPIs, charts, conditional formatting, and advanced DAX measures.

Prerequisites
Data set
Power BI
Problem Solving

**Problem statment:**
The car dealership wants a clear, data-driven understanding of its sales performance across different years, brands, fuel types, and models.
The goal is to build an interactive Power BI dashboard that helps the business:
Monitor overall sales performance using KPIs
Compare YTD, MTD, and YoY metrics
Identify best- and worst-performing brands and models
Understand how factors like fuel type, transmission, and body type influence sales
View historical trends and seasonality using week/month/year charts
Enable managers to filter insights by time, model

**Dataset Description:**
The dataset contains car sales transactions with fields like Date, Brand, Model, Body Type, Fuel Type, Transmission, and Price. After cleaning and standardizing the data, additional date fields (Year, Month, Week) were created using a Calendar table to enable time-based analysis and KPI calculations
<img width="1458" height="767" alt="Data set Sample" src="https://github.com/user-attachments/assets/a22cd143-3811-4f55-a3ad-c55f592b712d" />

🎯 Key Objectives

* Build a complete Power BI dashboard from raw data to final visualization
* Clean and prepare car sales data
* Create a dynamic Calendar table and date intelligence metrics
* Build advanced DAX measures such as YTD, MTD, YoY Growth, and Max Sales Point
* Design user-friendly visuals with professional formatting
* Implement conditional formatting and KPI indicators

Skills Demonstrated
Data cleaning & transformation
Power Query
DAX (YTD, MTD, YoY, CALCULATE, ALLSELECTED, MAXX, TOTALYTD)
Data modeling
Dashboard design

KPI creation & formatting
🧹 1. Data Cleaning & Preparation

* Replaced incorrect values and standardized fields
* Ensured data types were correctly assigned (Date, Numeric, Text)
* Verified dataset quality—minimal corrections needed
* Applied the cleaning steps into the Power BI data model

✔ Result: A clean and reliable dataset for analysis.

2. Calendar Table & Date Intelligence
A dedicated Calendar Table was created to support all time-intelligence functions.

Key calculated columns:

* Year
* Month (Full & Short)
* Week
* Quarter
* Year-Month

Used in measures like:

* YTD Total Sales
* YoY Growth
* MTD Average Price

✔ The dashboard automatically detects the latest year for YTD calculations.

3. KPI Metrics Created**

 ✔ Total Sales: A simple aggregation of car sales revenue.
 ✔ Year-on-Year Growth:Using SAMEPERIODLASTYEAR for comparison.
 ✔ Month-to-Date (MTD) Sales & Average Price:ormatted properly to display in thousands with two decimals.
 ✔ Total YTD Sales: Automatically selects the latest year based on data.

Each KPI dynamically updates based on slicers (Year, Brand, Dealer)

4. Visualizations & Charts

Six main charts were created as per the project requirements:

1. Sales Trend Over Time
2. Sales by Car Brand
3. Sales by Body Type
4. Sales by Transmission
5. Sales by Fuel Type
6. Top-performing Months / Weeks

✔ Dynamic filters applied using slicers (Year, Model, Dealer).
✔ Visuals designed with clean spacing, proper alignment, and thematic color palette.

5. DAX Calculations

🔹 SUM(), CALCULATE(), TOTALYTD(), SAMEPERIODLASTYEAR(): Used to create dynamic date-based metrics.

🔹 IF(), MAXX(), ALLSELECTED(): Used for peak sales detection (max point in charts).

Power BI Dashboards:

<img width="1284" height="724" alt="Car_sales_Dashboard" src="https://github.com/user-attachments/assets/8e6dc959-713e-4f23-8cef-e3b3921189ff" />

Dashboard Highlights:

KPI cards for major performance metrics
Trend analysis with max sales point identification
Sales by brand, fuel type, and transmission
Monthly and yearly breakdowns
Clean UI with conditional formatting and drill-down interactions

Key Insights

| Insight Area             | Summary                                                                                      |
| ------------------------ | -------------------------------------------------------------------------------------------- |
| **Sales Trends**         | Identified clear monthly and weekly patterns showing peak and low sales periods.             |
| **Top Categories**       | Certain brands, models, and body types consistently generated the highest sales.             |
| **Pricing Behavior**     | Average sale price varied significantly across models, transmission types, and fuel options. |
| **YTD Performance**      | Year-to-date sales revealed growth or decline compared to previous years.                    |
| **MTD Insights**         | Month-to-date metrics provided real-time visibility into current month performance.          |
| **Customer Preferences** | Strong preference observed for specific fuel types and transmission types.                   |
| **Revenue Contribution** | A small number of brands/models contributed the majority of total revenue.                   |
| **Max Sales Periods**    | Peak weeks and months identified using DAX to highlight highest-performing periods.          |


Conclusion

This project showcases a full end-to-end Power BI workflow:

✔ Data Import → Cleaning → Modeling → DAX → Visualization → Polishing
✔ Suitable for portfolios, GitHub projects, and job interviews
✔ Demonstrates strong BI, analytical, and dashboard-design skills




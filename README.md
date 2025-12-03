# Car-Sales-Analysis-End-to-End-Power-BI-Dashboard-
Built an interactive Power BI dashboard for car sales analysis. Loved creating dynamic visuals, DAX measures (YTD, MTD, YoY) and a clean UI. This project covers data cleaning, modeling making the analysis both powerful and enjoyable.



## 📌 **Project Overview**

This project demonstrates how to build a fully dynamic and interactive **Power BI dashboard** for analyzing car sales data. The dashboard highlights business performance using KPIs, charts, conditional formatting, and advanced DAX measures.



🎯 **Key Objectives**

* Build a complete Power BI dashboard from raw data to final visualization
* Clean and prepare car sales data
* Create a dynamic Calendar table and date intelligence metrics
* Build advanced DAX measures such as YTD, MTD, YoY Growth, and Max Sales Point
* Design user-friendly visuals with professional formatting
* Implement conditional formatting and KPI indicators


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

**3. KPI Metrics Created**

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

🔹 **SUM(), CALCULATE(), TOTALYTD(), SAMEPERIODLASTYEAR(): Used to create dynamic date-based metrics.

🔹 **IF(), MAXX(), ALLSELECTED(): Used for peak sales detection (max point in charts).

The final dashboard provides:

* Complete business sales overview
* Drill-down capability by year, brand, transmission, and fuel type
* Dynamic KPIs with YTD, MTD, YoY analysis
* Trend analysis with max-point detection
* Clean, intuitive interface for decision-making


Conclusion

This project showcases a full end-to-end Power BI workflow:

✔ Data Import → Cleaning → Modeling → DAX → Visualization → Polishing
✔ Suitable for portfolios, GitHub projects, and job interviews
✔ Demonstrates strong BI, analytical, and dashboard-design skills


# 📦 **Suggested Files to Upload to GitHub**

* `Car_Sales_Dataset.csv` (cleaned or raw)
* `.pbix` Power BI file
* `README.md` (use this summary)
* Screenshot folder of final dashboard
* DAX_Measures.txt


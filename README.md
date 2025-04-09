# Excel-Bus-Transportation-Analysis-Dashboard
"Analyzes bus transportation data to optimize routes, track performance, and improve efficiency."

## 🚍 Bus Transportation Analysis Dashboard Part 1

A complete data analysis project using Microsoft Excel tools like Power Query, Power Pivot, DAX, and M-code to analyze a two-year transportation system.

## 📌 Objective 
The objective of this project is to build a comprehensive Bus Transportation Dashboard that evaluates:

1) Overall passenger trends over two years

2) Route efficiency and utilization levels

3) Time-based ride analysis (AM/PM, peak/off-peak hours)

4) Weekly and monthly rider distribution

5) Categorization of buses into utilization segments

This dashboard helps make strategic decisions by identifying patterns, gaps, and improvement opportunities.

##📊 Key Insights from the Dashboard##
**1)👥 Total Passengers**
6,587 passengers recorded over the time.

**2)🚍 Average Riders per Trip**
Each trip had an average of 33 passengers.

**3)🗺️ Route Utilization**
Busiest Route: East-West Express

**4)Least Busy Route:**  South Line

**5)🕒 Peak vs Off-Peak Hours**
Peak Hour: 11:41 AM
Off-Peak Hour: 12:34 PM

**6)📅 Monthly Rider Distribution**

**7)Highest Ridership Month:**  
December (5,654 passengers)

**8)Significant YoY Change:**  An 83.50% decrease in total rider count from 2023 (5,654) to 2024 (933)

**9)📆 Weekly Rider Distribution**
Most Riders: Sunday (1,185)

**10)Least Riders:**  Saturday (706)

**11)☀️🌙 Time of Day**
AM Riders: 35.39%
PM Riders: 64.61%

**12)🔄 Bus Utilization Categories**
43% Over-Utilized
35% Well-Utilized
23% Under-Utilized

# 🧠 Recommendations
1) This dashboard enables better operational decisions by:
2) Monitoring real-time bus usage to optimize routes
3) Managing traffic flow by encouraging off-peak travel
4) Identifying and correcting under-utilized routes
5) Using data-backed insights for marketing strategies
6) Supporting resource reallocation to improve service delivery

## 🧰 Backend Work Using Power Query & Power Pivot part 2:
The backend work was meticulously handled in Excel using Power Qery and Power Pivot, including:

## 1) 🔍 Data Sources Used:
1) Dim_buses
2) Dim_demographics
3) Dim_routes
4) Facttable_ridership
5) Dim_DateTable

**Calculation Sheet**

🔧 Transformations Applied
🧓 Age Grouping

**- Age values from Dim_demographics were grouped using:**

Add Conditional Column

Add Custom Column

**-🕑 Time Group Creation**
Used custom logic in Facttable_ridership to segment time into groups

**-📊 Bus Utilization %**
Added as a custom column

Converted into three segments using conditional logic: Over, Well, Under-utilized

**-📆 Date Table Enhancements**
Extracted Year, Month, Day, Week Number, and Week Type

Week Type created with logic: Sunday = 0, Saturday = 6 → Weekend; Others → Weekday

**🔄 Merging & Data Formatting**
Columns merged using the Merge Column option

Data types updated (e.g., Text, Date, Time)

**🔗 Data Model & DAX Measures**
Created relationships between all tables using Power Pivot

**Defined Key Performance Indicators (KPIs) Using DAX:**

**KPI	Formula**
1) Total Transactions	=COUNTROWS(Facttable_ridership)
2) Average Age	=AVERAGE(Dim_demographics[Age])
3) Total Riders	=SUM(Facttable_ridership[NumberOfRiders])
4) Avg Riders per Trip	=AVERAGE(Facttable_ridership[NumberOfRiders])

# 📚 My Learning Outcomes#
During this project, I explored the following Excel tools and concepts:
1) Power Query Editor
2) Conditional Column & Custom Column
3) Column Merging & Data Cleaning
4) Data Type Formatting
5) Power Pivot Data Model
6) DAX Formulas for KPIs
7) Date Hierarchies & Week Segments

M-code for advanced logic implementation

**✅ Final Outcome**
The final dashboard presents a data-driven, visually informative overview of bus operations over two years. It successfully uncovers:

Usage trends (monthly, weekly, hourly)

Route efficiency

Passenger behavior

Bus utilization insights

This helps transportation authorities make data-informed decisions and optimize public transport services.

# 📧 Contact

Mahnoor Naseer Ahmad

✉️ mahnoornoorg57@gmail.com

🔗 Follow me on LinkedIn for more updates

https://www.linkedin.com/in/mahnoor-naseer-ahmad/



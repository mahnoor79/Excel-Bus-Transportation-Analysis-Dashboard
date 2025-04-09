# Excel-Bus-Transportation-Analysis-Dashboard
"Analyzes bus transportation data to optimize routes, track performance, and improve efficiency."

**🚍 Bus Transportation Analysis Dashboard**

A complete data analysis project using Microsoft Excel tools like Power Query, Power Pivot, DAX, and M-code to analyze a two-year transportation system.

📌 Objective
The objective of this project is to build a comprehensive Bus Transportation Dashboard that evaluates:

Overall passenger trends over two years

Route efficiency and utilization levels

Time-based ride analysis (AM/PM, peak/off-peak hours)

Weekly and monthly rider distribution

Categorization of buses into utilization segments

This dashboard helps make strategic decisions by identifying patterns, gaps, and improvement opportunities.

📊 Key Insights from the Dashboard
👥 Total Passengers
6,587 passengers recorded over the time.

🚍 Average Riders per Trip
Each trip had an average of 33 passengers.

🗺️ Route Utilization
Busiest Route: East-West Express

Least Busy Route: South Line

🕒 Peak vs Off-Peak Hours
Peak Hour: 11:41 AM

Off-Peak Hour: 12:34 PM

📅 Monthly Rider Distribution
Highest Ridership Month: December (5,654 passengers)

Significant YoY Change: An 83.50% decrease in total rider count from 2023 (5,654) to 2024 (933)

📆 Weekly Rider Distribution
Most Riders: Sunday (1,185)

Least Riders: Saturday (706)

☀️🌙 Time of Day
AM Riders: 35.39%

PM Riders: 64.61%

🔄 Bus Utilization Categories
43% Over-Utilized

35% Well-Utilized

23% Under-Utilized

🧠 Recommendations
This dashboard enables better operational decisions by:

Monitoring real-time bus usage to optimize routes

Managing traffic flow by encouraging off-peak travel

Identifying and correcting under-utilized routes

Using data-backed insights for marketing strategies

Supporting resource reallocation to improve service delivery

🧰 Backend Work Using Power Query & Power Pivot
The backend work was meticulously handled in Excel using Power Query and Power Pivot, including:

🔍 Data Sources Used:
Dim_buses

Dim_demographics

Dim_routes

Facttable_ridership

Dim_DateTable

Calculation Sheet

🔧 Transformations Applied
🧓 Age Grouping
Age values from Dim_demographics were grouped using:

Add Conditional Column

Add Custom Column

🕑 Time Group Creation
Used custom logic in Facttable_ridership to segment time into groups

📊 Bus Utilization %
Added as a custom column

Converted into three segments using conditional logic: Over, Well, Under-utilized

📆 Date Table Enhancements
Extracted Year, Month, Day, Week Number, and Week Type

Week Type created with logic: Sunday = 0, Saturday = 6 → Weekend; Others → Weekday

🔄 Merging & Data Formatting
Columns merged using Merge Column option

Data types updated (e.g., Text, Date, Time)

🔗 Data Model & DAX Measures
Created relationships between all tables using Power Pivot

Defined Key Performance Indicators (KPIs) using DAX:

KPI	Formula
Total Transactions	=COUNTROWS(Facttable_ridership)
Average Age	=AVERAGE(Dim_demographics[Age])
Total Riders	=SUM(Facttable_ridership[NumberOfRiders])
Avg Riders per Trip	=AVERAGE(Facttable_ridership[NumberOfRiders])
📚 My Learning Outcomes
During this project, I explored the following Excel tools and concepts:

Power Query Editor

Conditional Column & Custom Column

Column Merging & Data Cleaning

Data Type Formatting

Power Pivot Data Model

DAX Formulas for KPIs

Date Hierarchies & Week Segments

M-code for advanced logic implementation

✅ Final Outcome
The final dashboard presents a data-driven, visually informative overview of bus operations over two years. It successfully uncovers:

Usage trends (monthly, weekly, hourly)

Route efficiency

Passenger behavior

Bus utilization insights

This helps transportation authorities make data-informed decisions and optimize public transport services.

📧 Contact
Mahnoor Naseer Ahmad
✉️ mahnoornoorg57@gmail.com
🔗 Follow me on LinkedIn for more updates
(Insert your LinkedIn link here)



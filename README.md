1. Project Overview
Title: Passenger Trend Analysis
Author: Pvs Sampath
Purpose: Analyzing international passenger trends across countries, months, and years using Power BI.

2. Data Source
Dataset: Contains information on passenger traffic by country, month, and year.
Columns:
Country – Name of the country.
Month – Travel month.
Total Passengers – Number of passengers traveling.
Year – Corresponding year of the travel data.

3. Dashboard Features
Key Metrics:
Total Passengers: 4 billion
Years of Data: 32 years
Total Destinations (Countries): 46 unique destinations
Visuals & Insights:
Most Travelled Destinations:
Top 10 countries with the highest passenger volume.
Weekday Passenger Trends:
Passenger traffic variation across weekdays.
Total Passengers by Quarter:
Pie chart distribution of passengers across four quarters.
Monthly Passenger Trends:
Line chart showing passenger variations across months.
Top 3 Travel Destinations (2020 & 2021):
Year-wise breakdown of the most traveled destinations.

4. Calculated Measures (DAX)
Distinct Count of Countries:
DAX
Copy
Edit
# Countries = DISTINCTCOUNT(Data[Country])
Total Passengers (Summation):
DAX
Copy
Edit
Total Passengers = SUM(Data[Total Passengers])
Passenger Trends by Year/Month/Quarter:
Aggregated calculations for year-wise, month-wise, and quarter-wise trends.

5. Filters & Slicers Used
Country Filter
Year Filter
Month Filter
Quarter Filter

6. Dashboard Design
Color Theme: Teal and White
Visualization Type: Bar charts, Line charts, Pie charts, and KPI cards.
Data Modeling: Used Measure_Table for calculated metrics and Data Table for raw dataset.

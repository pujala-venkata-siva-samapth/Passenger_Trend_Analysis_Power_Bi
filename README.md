# Passenger Trend Analysis

## Dataset Description
The dataset used for this project includes the following columns:
- **Country**: Name of the country.
- **Month**: Travel month.
- **Year**: Corresponding year.
- **Total Passengers**: Number of passengers traveling.

## Questions Solved and Approach
1. **Find the total number of unique countries in the dataset.**  
   - The query uses `DISTINCTCOUNT` in Power BI.

2. **Identify the top 10 most traveled destinations based on passenger volume.**  
   - The query sorts countries by `SUM(Total Passengers)` and selects the top 10.

3. **Analyze passenger variation across weekdays and months.**  
   - The query groups by `Month` and aggregates passenger counts.

4. **Calculate total passengers by year.**  
   - The query performs a `SUM(Total Passengers)` grouped by `Year`.

5. **Determine the quarter-wise distribution of passengers.**  
   - The query uses `QUARTER()` function in Power BI.

6. **Compare total passengers for different countries over the years.**  
   - A line chart visualizes trends for selected countries.

7. **Calculate moving averages for passenger trends over months.**  
   - The query applies the `AVERAGE` function over a rolling period.

8. **Identify the country with the highest passenger traffic.**  
   - The query ranks countries based on `SUM(Total Passengers)`.

## Tools and Technologies Used
- **Data Analysis Tool**: Power BI  
- **Query Language**: DAX (Data Analysis Expressions)  
- **Dataset Source**: International Passenger Traffic Dataset  

## How to Run the Project
1. Import the dataset into Power BI.  
2. Clean and transform data using Power Query.  
3. Create calculated measures using DAX formulas.  
4. Build visualizations such as line charts, bar charts, and KPI cards.  
5. Analyze the results to extract insights into passenger trends.  

## Conclusion
This project leverages Power BI for data visualization and analysis of international passenger trends.  
The queries explore patterns, such as country-wise traffic, seasonal variations, and top destinations, providing actionable insights for decision-making.  

## Author
**Pvs Sampath**

# Airlines Dashboard
Dashboard Link : Power BI Report
(https://drive.google.com/file/d/1rrWYaDDLwx9O3sltMzYdPYo63_lBrYA7/view?usp=sharing)
### Problem Statement:
This dashboard helps airlines analyze customer satisfaction and operational efficiency. It identifies improvement
areas based on customer feedback and highlights key performance metrics such as flight delays and cancellations. By
leveraging this dashboard, airlines can work towards enhancing their services and minimizing delays.
Key findings:
Flight Delays: The average delay for arrivals and departures is 15 minutes, which should be reduced.
Cancellations Impact: A small cancellation rate of 1.54% can significantly affect passenger experience.
### Report Structure:
The Power BI report consists of four pages, accessible via navigation buttons at the bottom.

1. Home (Default Landing Page)
- Total Trips: 5M
- Average Trips per Month: 444.41K
- On-Time Performance: 59.78%
- Early Arrivals: 18.99%
- Delays: 21.28%
- Cancellations: 1.54%
- Trips by Month, Airline, and Airport
- State-based Filtering Option
2. Global Flights Overview
- Flights Breakdown by Region & Country
- Passenger Demographics & Travel Preferences
- Class-wise Distribution of Customers
- Interactive Bookmarks for Deep Dive Analysis
3. Flight Cancellations
- Breakdown of Cancelled Flights by Airline, Route & Seasonality
- Factors Leading to Cancellations
- Comparative Analysis Between Airlines
- Drill-through to Detailed Cancellation Insights
4. Delays & On-Time Performance
- Delay Trends by Time, Airline & Route
- Correlation Between Delay Causes & Customer Satisfaction
- Performance Metrics for Airlines with the Least & Most Delays
- Interactive Filters for Customized Analysis
### Steps Followed in Report Creation:
1. Data Loading & Preparation:
- Imported dataset (CSV format) into Power BI Desktop.
- Conducted data cleansing and transformations in Power Query Editor.
- Checked for missing values; ignored nulls in delay calculations.

2. Data Modelling:
- Created calculated columns and measures using DAX.
- Grouped customers into age categories.
- Added KPI measures for total trips, delays, and cancellations.

3. Visualizations & Interactivity:
- Used slicers for filtering data by Staes, Origin, Destination, Date, and Cancellation Reason.
- Integrated drill-throughs and Detail Pages to enable deep-dives into specific metrics.
- Applied bookmarks for toggling between different views.
- Used card visuals for key KPIs (delays, on-time percentage, cancellations, and total trips).
- Incorporated bar charts, line charts, and rating visuals for comparative insights.

4. Publishing & Sharing:
- Published report to Power BI Service for accessibility.
- Enabled interactions between visuals for better exploration.

### Key Insights
A. A total of 5 million flights took off, averaging 444 K trips per month.  
B. The busiest month was July , recording 521 K trips.  
C. In terms of punctuality, 59.78% of flights were on time , while 21.28% experienced delays , and
1.54% were cancelled.  
D. The top airline was WN , operating 1.26M trips , while ATL stood out as the busiest airport ,
handling 350 K flights. The most-travelled route was LAX to JFK , with 4,913 trips recorded.  
E. A total of 4,807 aircraft travelled 2.65M hours , covering an impressive distance of approximately
1 B kilometres across 6,847 unique routes.  
F. The airline with the most cancellations was WN , accounting for 16,043 flights , while ORD was the
airport with the highest cancellations, totalling 8,548 flights.  
G. Out of 89,884 total cancellations , the primary reason was weather-related disruptions , affecting
48,851 flights.  
H. The highest number of cancellations occurred in February , with 20,517 flights cancelled.  
I. A total of 1.23M flights experienced delays, with June recording the highest number at 133K
delays.  
J. The airport with the most delays was ORD , reporting 77,889 delayed flights , while WN was the
airline with the highest number of delays, totalling 285K flights.  
This Power BI dashboard provides a comprehensive view of airline operations, and performance trends, enabling data-
driven decision-making for enhanced efficiency and satisfaction.

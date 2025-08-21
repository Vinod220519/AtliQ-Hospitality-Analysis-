## AtliQ-Hospitality-Analysis-


**Project Overview**

I developed this analysis for AtliQ Hospitality Analysis, a fictional luxury hotel chain in India (Mumbai, Delhi, Hyderabad, Bangalore). Inspired by Codebasics Resume Challenge #, it addresses revenue declines from competition. I imported aggregated Excel data, cleaned it via Power Query, built a star schema, and created interactive dashboards with DAX for insights like what-if cancellation scenarios.

Data spans May-July 2022, totaling ~1.708B INR revenue. Focus: Bookings (~134K), cancellations (~25%), occupancy (~57%), RevPAR/ADR trends.

**Data Sources**

Excel file with 11 sheets (some truncated in view, full from challenge):
•	Bookings by Platform: "Others" leads (55K).
•	Cancellation %: Delhi highest (25.06%).
•	Capacity vs. Bookings: Elite most cancellations (4,115).
•	Weekday/Weekend: Weekends higher occupancy (62.64%), RevPAR (7,972 INR).
•	Loss by Cancellation: Mumbai ~116M INR.
•	Realisation % by ADR: Logtrip tops (70.59%, ADR 12,710 INR).
•	Revenue by Category/City: Luxury 1052M; Mumbai 669M.
•	Property Metrics :  Includes 7 properties per city (e.g., Hyderabad: Atliq Bay, Blu, City, Exotica, Grands, Palace; similar for others), with details like RevPAR, ADR, DSRN (rooms), realisation, cancellation, ratings.
•	Trends: June occupancy varies (50-62%).

Research and Industry Context :                                                                                                                                               
Researched 2022 Indian hospitality benchmarks: Occupancy ~60-65%, ADR ~10-15K INR, cancellations 20-30%. AtliQ aligns but can improve.   

•	Data Model: Star schema linking facts (revenue/bookings) to dimensions (cities/properties).                                                      
•	DAX Measures: Total Revenue, Avg Occupancy, Cancellation Rate. What-If: Parameter for 60% cancellations on 100 bookings yields 40 confirmed.                        

**Key Findings and Insights**                                                             
•	Mumbai: 39% revenue, high losses (116M).                                   
•	Platforms: "Others" volume high, direct offline best ADR.                                         
•	Day Variance: Weekends +12% occupancy – promote packages.                                           
•	Rooms: Presidential underutilized.                                         
•	Properties: High-rated (e.g., Atliq Exotica 4.33) perform better.                               
•	Trends: June dips suggest seasonal strategies        

**Tools Used**                                     
Power BI (DAX, visuals), Excel.

**Recommendations**                                                                                                                                                           •	Non-refunded deals for Mumbai: Reduce high absolute losses from volume * rate, retaining more via penalties.
•	Company discounts for weekdays: Boost lower occupancy/revenue (~50M potential).
•	Spa bundles for Presidential rooms: Address low demand, targeting 15K ADR for ~10M gain.
•	LogTrip offers for June: Leverage high ADR to counter seasonal trends.
•	Upgrades for Luxury ratings: Improve guest satisfaction in luxury category.


Live Dashboard Link:                                           
https://app.powerbi.com/groups/me/reports/ae0cc534-893f-4f85-a65f-fef1ccb11c49/386410fcc4cb435e6295?experience=power-bi&bookmarkGuid=f8ebdad1449ee450db7d

Project Overview :
This end-to-end Power BI project focuses on optimizing delivery operations for a multi-city restaurant network. The dashboard transforms raw transactional data into actionable logistics insights, focusing on three pillars: Efficiency, Reliability, and Customer Satisfaction.

Data Source :
The analysis is based on a dataset of 10,000 delivery records, including timestamps, geographic coordinates (Lat/Long), order status, and customer feedback.

Technical Key Features :
Time Intelligence & Temporal Analysis: Developed a custom DAX Calendar table to analyze order flows by "Hour of Day" and "Day of the Week," identifying peak demand periods.
Logistics KPI Suite: Engineered critical measures including SLA Success Rate (deliveries under 40 min), Cancellation Rate, and Average Delivery Duration.
Geospatial Visualization: Integrated Latitude/Longitude data to map delivery density and regional performance across major US cities.
Root Cause Diagnostic: Created a filtered "Cancellation Analysis" view to isolate specific supply chain bottlenecks (e.g., driver availability vs. restaurant delays).
Advanced Data Cleaning: Performed complex ETL in Power Query to handle null values in canceled orders and synchronize date/time formats for accurate relationship modeling.

Executive Insights :
The "Speed-to-Rating" Bridge: Statistical correlation analysis confirms a sharp decline in customer ratings once delivery exceeds the 40-minute threshold.
Operational Peaks: Data reveals mid-day and evening surges, providing a clear staffing roadmap for logistics managers.
Cancellation Drivers: By isolating non-delivered orders, the dashboard highlights that "Driver Availability" is the primary factor for service failure in high-density areas like New York.

Tools Used  :
Power BI Desktop: DAX (Data Analysis Expressions) & Data Visualization.
Power Query: ETL processes and data normalization.
GitHub: Version control and documentation.

How to use
Open Restaurants Logistics.pbix in Power BI Desktop.
Use the slicers to deep-dive into specific local performances.
Explore the Visualization et the data represented to understand the factors driving low customer ratings and their preferences.

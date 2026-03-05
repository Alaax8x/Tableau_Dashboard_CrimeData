Project Summary

This project focuses on analyzing crime data using SQL and a dashboard to support decision-making. The goal is to help police departments identify crime hotspots, understand crime patterns, and allocate resources effectively.

The project begins by explaining the importance of data analytics in organizations, where data is treated as a valuable asset for improving decision-making. Using Business Analytics and OLAP (Online Analytical Processing), the project builds a dashboard that visualizes crime data collected from police departments across England. 

Dashboard_SQL_on CrimeData

The dashboard includes several visualizations to analyze crime patterns:

Stacked bar chart to show the number of crimes by police station and crime type, revealing that Meanwood has the highest crime rates, with violent crime being the most common.

Treemap to display police work allocation across different crime types, showing that violent crimes receive the most resources.

Heatmap to compare crime types with the number of witnesses, indicating that violent crimes often have the most witnesses.

Bar chart analyzing work allocation depending on witness type.

Scatter plot showing relationships between crime status, station location, and crime type, helping identify areas with many open cases.

These visualizations help decision-makers understand where crimes occur, their circumstances, and how police resources are used. 

Dashboard_SQL_on CrimeData

In addition to the dashboard, the project implements database programming using PL/SQL:

A stored procedure to update crime status safely (OPEN, CLOSED, ESCALATE) while preventing errors, ensuring valid IDs, and automatically managing the closing date.

A function to calculate how long a crime has been open (in days or months), even if the crime is still open.

A package that groups the procedure and function together for easier management and reuse.

Finally, the system is integrated into an application interface with buttons that allow users to update crime status or delete records directly from the database.

Overall, the project demonstrates how data visualization, SQL procedures, and database functions can be combined to analyze crime data and support better policing decisions. 

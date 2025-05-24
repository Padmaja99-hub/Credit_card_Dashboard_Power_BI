# Credit_card_Dashboard_Power_BI
Credit card Dashboard Power BI<br />
Project Objective: To develop a weekly dashboard providing real-time insights into key performance metrics and trends for credit card operations.<br />
Dataset: Customer dataset with customer details (customer.csv) and Credit card data showing their credit usage info (credit_card.csv) is used
Steps:
1.	Project Overview & Planning
•	Defined the business problem: Analyze credit card customer and transaction data.
•	Identified key KPIs: Revenue trends, customer segmentation, utilization ratios, and delinquency rates.
2.	Data Extraction & Integration
•	Imported customer and transaction data from a SQL Database using SQL queries.
•	Combined multiple datasets (CSV files) into Power BI using Power Query.
•	Ensured data integrity: Validated data types, checked for nulls, duplicates, and consistency.
3.	 Data Cleaning & Transformation
•	Performed data cleaning using Power Query (removed nulls, fixed headers).
•	Created custom columns using DAX: Age Group, Income Group, Week Number.
•	Calculated revenue, acquisition costs, and week-on-week revenue changes.
4.	Data Modeling & DAX Calculations
•	Established relationships between tables.
•	Created calculated columns and measures (e.g., Total Revenue, % Change WoW).
•	Used DAX functions like SWITCH(), WEEKNUM(), IF(), and DIVIDE() for advanced logic.
5.	Dashboard Development
•	Designed two dashboards:
i)	Credit Card Customer Report
ii)	Credit Card Transaction Report
•	Incorporated filters by Gender, Income Group, Card Type, and Quarter.
•	Applied clean formatting: Color themes, visual hierarchy, and responsive layout.
6.	 Visualization Customization
•	Used bar charts, stacked columns, KPIs, and slicers for interaction.
•	Added titles, data labels, tooltips, and legend formatting for clarity.
•	Created a weekly trend analysis view for actionable insights.
7.	Weekly Updates & Automation
•	Integrated additional data files for weekly refresh.
•	Ensured dynamic updates with Power BI’s Refresh functionality.
•	Highlighted trends using automatically updated week-over-week metrics.



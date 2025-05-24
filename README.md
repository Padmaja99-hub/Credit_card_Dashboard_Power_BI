# Credit_card_Dashboard_Power_BI
Credit card Dashboard Power BI<br />
Project Objective: To develop a weekly dashboard providing real-time insights into key performance metrics and trends for credit card operations.<br />
Dataset: Customer dataset with customer details (customer.csv) and Credit card data showing their credit usage info (credit_card.csv) is used<br />
Steps:<br />
1.	Project Overview & Planning<br />
•	Defined the business problem: Analyze credit card customer and transaction data.<br />
•	Identified key KPIs: Revenue trends, customer segmentation, utilization ratios, and delinquency rates.<br />
2.	Data Extraction & Integration<br />
•	Imported customer and transaction data from a SQL Database using SQL queries.<br />
•	Combined multiple datasets (CSV files) into Power BI using Power Query.<br />
•	Ensured data integrity: Validated data types, checked for nulls, duplicates, and consistency.<br />
3.	 Data Cleaning & Transformation<br />
•	Performed data cleaning using Power Query (removed nulls, fixed headers).<br />
•	Created custom columns using DAX: Age Group, Income Group, Week Number.<br />
•	Calculated revenue, acquisition costs, and week-on-week revenue changes.<br />
4.	Data Modeling & DAX Calculations<br />
•	Established relationships between tables.<br />
•	Created calculated columns and measures (e.g., Total Revenue, % Change WoW).<br />
•	Used DAX functions like SWITCH(), WEEKNUM(), IF(), and DIVIDE() for advanced logic.<br />
5.	Dashboard Development<br />
•	Designed two dashboards:<br />
i)	Credit Card Customer Report<br />
ii)	Credit Card Transaction Report<br />
•	Incorporated filters by Gender, Income Group, Card Type, and Quarter.<br />
•	Applied clean formatting: Color themes, visual hierarchy, and responsive layout.<br />
6.	 Visualization Customization<br />
•	Used bar charts, stacked columns, KPIs, and slicers for interaction.<br />
•	Added titles, data labels, tooltips, and legend formatting for clarity.<br />
•	Created a weekly trend analysis view for actionable insights.<br />
7.	Weekly Updates & Automation<br />
•	Integrated additional data files for weekly refresh.<br />
•	Ensured dynamic updates with Power BI’s Refresh functionality.<br />
•	Highlighted trends using automatically updated week-over-week metrics.<br />



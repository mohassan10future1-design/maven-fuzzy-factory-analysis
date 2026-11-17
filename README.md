Maven Fuzzy Factory: Sales and Customer Behaviour Analysis
In this project I cleaned e-commerce data, answered business questions with SQL, built a Power BI dashboard, and wrote recommendations for management.
Tools: Excel / Power Query, SQL Server, Power BI
________________________________________
Business Problem
Maven Fuzzy Factory sells plush toys online. Management wants to know:
•	How the website performs
•	Which marketing channels bring sales
•	Which products sell the most and get refunded the most
•	How to increase revenue and conversion


Main Findings
1.	Revenue grew from $393K in 2013 to $1.08M in 2014.
2.	Paid search (gsearch + bsearch) brings 80% of the traffic.
3.	Mobile converts at 3.09%, desktop at 8.50%.
4.	Socialbook is the weakest channel (3.21% conversion).
5.	One product (Mr. Fuzzy) makes 62% of the revenue.
6.	Sugar Panda has the highest refund rate (6.04%).
7.	November and December 2014 made 25% of that year's revenue.

Data
Table	Rows
website_sessions	472,871
orders_mav	32,313
order_items	40,025
order_item_refunds	1,731
products	4


What I Did
Task	Work	Output
1. Data preparation	Checked nulls, duplicates, data types and keys. Cleaned in Excel and Power Query.	DATA_QUALITY.md
2. SQL analysis	Answered 10 business questions.	sql/maven_sql_analysis.sql
3. Power BI dashboard	KPI cards, charts, and slicers.	dashboard/
4. Insights	7 findings with recommendations.	SUMMARY.md

I did not use website_pageviews. No question needed it, and my copy was cut at Excel's row limit. More in DATA_QUALITY.md.
Author
Mohahammed hassan, Data Analyst




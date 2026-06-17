# Power-BI-Assignment-
The focus of this assignment is on data import, transformation, cleansing, aggregation, and relationship modelling using Power BI and Power Query Editor, while ensuring consistency, accuracy, and business relevance of the prepared data model.
 Project Overview
Business Problem: solving The dataset contains multiple related files representing order-level, product-level, and sales target information.
•	Objective: Explain the over all order details and sales target by using this dashboard.
•	Target Audience: Identify the primary users (e.g., order id ,order details, Sales Operations).
🗃️ Data Sources & Architecture
•	Source Systems: List sources like  local Excel files.
•	Data Volume: Note the rough row counts or timeframe covered.
•	Storage Mode: Specify if using Import, DirectQuery, or Composite mode.
⚙️ Data Transformation (ETL)
•	Tool Used: Power Query Editor.
•	Key Cleanups: List standard transformations applied to raw data (e.g., merging, unpivoting).
•	Custom Functions: Mention any customized M code scripts used.
🧠 Data Model & DAX
•	Model Type: State your schema design (e.g., Star Schema, Snowflake Schema).
•	Fact Tables: Name the primary transactional tables.
•	Dimension Tables: Name the lookup tables, including your dedicated Date table.
•	Key Measures:
•	Total Revenue = SUM('Sales Fact'[ExtendedAmount])
•	YoY Growth % = DIVIDE([Total Revenue] - [Prior Year Revenue], [Prior Year Revenue])
🖥️ Dashboard Features
•	Page 1: Overview:  find the relationship between all order details and sales table
•	💡 Key Insights
•	Trend A: First major business finding or behavior pattern identified.
•	Trend B: Actionable performance anomaly noted in the data.
•	Recommendation: Direct business action suggested based on the metrics.
🚀 How To Use
1.	Prerequisites: Ensure you have the latest Power BI Desktop installed.
2.	File Formats: Clone the repository to access the .pbix or .pbit file.
3.	Data Refresh: Change the source path under Data Source Settings to point to your data files.
4.	C:\Users\RAGAVI\Downloads\ASSITMENT.pbix
5.	ASSITMENT.pbix

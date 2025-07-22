# SAP-S-4-HANA-Data-Analysis

# Objective

This project focusses on analysis of SAP S/4HANA User Access Data from the STAD (System Trace and Analysis Data) report which aims to strengthen security, optimize system performance, and enhance decision-making through structured data insights. This project also aims to strengthen security and compliance monitoring by analyzing user access logs from SAP S/4HANA. Given the critical role of enterprise resource planning (ERP) systems in modern organizations, ensuring secure and efficient user access is essential for maintaining data integrity, preventing cyber threats, and adhering to regulatory standards.

# Tools Used
-SAP S/4 HANA (Data Source)
- Microsoft Excel (Data Processing)
- MsSQL
- Excel VBA (for dashboards)

# Description of project

1. Data Collection: Extracting SAP S/4HANA STAD Reports in Excel Format
•	STAD reports, which contain critical user access logs, transaction codes, response times, and system resource usage, were exported from SAP S/4HANA
•	The reports were extracted in Excel format, enabling ease of access and further processing.

2. Data Processing: Cleaning and Structuring Data Using 
•	Raw STAD data often contains inconsistencies such as missing values, duplicate entries, and formatting issues.
•	MSSQL was used to clean and preprocess the data, ensuring accuracy and completeness.
   
- Key steps in data processing included:
o	Removing duplicate or irrelevant records.
o	Standardizing date and time formats for consistency.
o	Filtering out system-generated transactions that do not contribute to user access analysis.

3. Storage & Management: Designing and Implementing an SQL Database
•	A relational database was created using SQL to store and manage large volumes of structured SAP STAD data efficiently.
•	Tables were designed to accommodate key fields such as user ID, transaction code, login timestamp, response time, CPU time, and terminal ID.
•	SQL indexing and query optimization techniques were implemented to enhance the speed and performance of data retrieval.

4. Data Analysis: Conducting SQL-Based Analysis for Security, Compliance, and Performance Monitoring
•	SQL queries were used to extract meaningful insights from the STAD data, focusing on:
o	User Access Monitoring: Identifying active users, frequent transactions, and unusual access patterns.
o	Security & Compliance Checks: Detecting unauthorized access, dormant accounts, and excessive login failures.
o	Performance Analysis: Measuring system response times, resource consumption, and identifying slow-performing transactions.

5. Visualization & Reporting: Developing Interactive Dashboards Using Excel VBA
•	Microsoft Excel VBA (Visual Basic for Applications) was used to automate the generation of analytical reports and dashboards.
•	Interactive dashboards were developed to provide real-time insights with user-friendly visualizations, including:
o	User Activity Trends: Graphs showing login frequencies, transaction execution patterns, and access trends over time.
o	Security Alerts: Conditional formatting and alerts for unauthorized access or abnormal system usage.
o	Performance Metrics: Response time distributions, CPU usage trends, and bottleneck identification charts.

# Result:- 

•	Compliance Monitoring: Defined compliance indicators and flagged any policy violations within the SAP system.
•	Performance Trends: Identified system load distribution patterns per user and monitored response time fluctuations to improve performance.
•	Data Storage Benefits: Implemented structured data storage in SQL, improving query efficiency and enhancing reporting accuracy
•	Security Enhancement: Detected unusual user activity patterns, which were further investigated to prevent security breaches.




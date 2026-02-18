<h1>Digital Allyship Toolkit – Data Warehouse & Analytics Project</h1>
Project Overview

Project Name: Digital Allyship Analytics Warehouse
Project Team: Lumera (Team 39)
Objective: Develop a modern data warehouse using SQL Server to consolidate platform usage, learning effectiveness, and user engagement data for analytical reporting and informed decision-making.

1. Business Context & Objectives

The Digital Allyship Toolkit platform collects valuable data on user engagement, learning progress, and behavioral outcomes. A data warehouse is needed to:

Track user progression through learning modules
Measure knowledge improvement and confidence growth
Analyze engagement patterns and retention rates
Support strategic decisions for content improvement
Demonstrate impact to stakeholders and funding partners
Key Business Questions:

Which modules have the highest completion rates?
What is the correlation between scenario-based learning and confidence growth?
Which user segments show the highest engagement?
How effective are different content formats (video vs. text)?
What factors predict successful certification completion?


<section>
<h2>Data Architecture</h2>
  The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

  1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.
   
<h3>Bronze Layer – Raw Data</h3>
<ul>
<li>User registrations</li>
<li>Module activity logs</li>
<li>Quiz attempts</li>
<li>Confidence assessments</li>
<li>Session activity</li>
<li>Certification records</li>
</ul>
<p>Stores application data exactly as collected.</p>

<h3>Silver Layer – Cleaned & Standardized Data</h3>
<ul>
<li>Remove duplicates</li>
<li>Standardize timestamps</li>
<li>Validate score ranges</li>
<li>Handle missing values</li>
<li>Normalize categorical values</li>
</ul>
<p>Creates reliable structured datasets.</p>

<h3>Gold Layer – Analytics & Business Logic</h3>
<p>Business-ready star schema optimized for reporting.</p>
<ul>
<li>Module Progress</li>
<li>Quiz Performance</li>
<li>User Sessions</li>
<li>Confidence Assessments</li>
<li>Certifications</li>
</ul>
</section>

<section>
  ## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics
</section>

<section>

<h2>Measured Impact Metrics</h2>
<ul>
<li>Module Completion Rate</li>
<li>Knowledge Improvement</li>
<li>Confidence Growth</li>
<li>Monthly Active Usage</li>
<li>30-Day Retention</li>
<li>Certification Achievement</li>
</ul>
</section>

<section>
<h2>Skills Demonstrated</h2>
<ul>
<li>SQL Development</li>
<li>Data Modeling</li>
<li>ETL Pipelines</li>
<li>Data Quality Validation</li>
<li>Dashboard Design</li>
<li>Impact Measurement Analytics</li>
</ul>
</section>

<section>
<h2>Tools Used</h2>
<table>
<tr><th>Tool</th><th>Purpose</th></tr>
<tr><td>PostgreSQL</td><td>Data warehouse database</td></tr>
<tr><td>DBeaver / pgAdmin</td><td>Database management</td></tr>
<tr><td>Python (Pandas)</td><td>Data transformation</td></tr>
<tr><td>Draw.io</td><td>Architecture & schema diagrams</td></tr>
<tr><td>Notion</td><td>Project management</td></tr>
<tr><td>Power BI / Tableau</td><td>Dashboard analytics</td></tr>
<tr><td>Mockaroo</td><td>Synthetic dataset generation</td></tr>
<tr><td>GitHub</td><td>Version control</td></tr>
</table>
</section>

<section>
<h2>Analytics Outputs</h2>
<h3>Learning Engagement</h3>
<ul>
<li>Module completion</li>
<li>Active users</li>
<li>Time spent</li>
</ul>

<h3>Learning Effectiveness</h3>
<ul>
<li>Pre vs post knowledge improvement</li>
<li>Quiz performance trends</li>
</ul>

<h3>Behavioral Impact</h3>
<ul>
<li>Confidence growth</li>
<li>Retention</li>
<li>Certification completion</li>
</ul>
</section>

<section>
<h2>Learning Outcome</h2>
<p>Understand how product analytics differs from business analytics and how data warehouses measure real-world impact.</p>
</section>

</body>
</html>

<h1>Digital Allyship Toolkit – Data Warehouse & Analytics Project</h1>

<h2>Project Overview</h2>
<p><strong>Project Name:</strong> Digital Allyship Analytics Warehouse</p>
<p><strong>Project Team:</strong> Lumera (Team 39)</p>
<p><strong>Objective:</strong> Develop a modern data warehouse using SQL Server to consolidate platform usage, learning effectiveness, and user engagement data for analytical reporting and informed decision-making.</p>

<section>
<h2>1. Business Context & Objectives</h2>
<p>The Digital Allyship Toolkit platform collects valuable data on user engagement, learning progress, and behavioral outcomes. A data warehouse is needed to:</p>
<ul>
<li>Track user progression through learning modules</li>
<li>Measure knowledge improvement and confidence growth</li>
<li>Analyze engagement patterns and retention rates</li>
<li>Support strategic decisions for content improvement</li>
<li>Demonstrate impact to stakeholders and funding partners</li>
</ul>

<h3>Key Business Questions</h3>
<ul>
<li>Which modules have the highest completion rates?</li>
<li>What is the correlation between scenario-based learning and confidence growth?</li>
<li>Which user segments show the highest engagement?</li>
<li>How effective are different content formats (video vs. text)?</li>
<li>What factors predict successful certification completion?</li>
</ul>
</section>

<section>
<h2>Data Architecture</h2>
<p>The architecture follows the Medallion Architecture using Bronze, Silver, and Gold layers.</p>

<h3>Bronze Layer – Raw Data</h3>
<p>Stores raw data exactly as received from source systems (CSV files into SQL Server).</p>
<ul>
<li>User registrations</li>
<li>Module activity logs</li>
<li>Quiz attempts</li>
<li>Confidence assessments</li>
<li>Session activity</li>
<li>Certification records</li>
</ul>

<h3>Silver Layer – Cleaned & Standardized Data</h3>
<ul>
<li>Remove duplicates</li>
<li>Standardize timestamps</li>
<li>Validate score ranges</li>
<li>Handle missing values</li>
<li>Normalize categorical values</li>
</ul>
<p>Creates reliable structured datasets ready for analytics.</p>

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
<h2>Project Components</h2>
<ul>
<li><strong>Data Architecture:</strong> Modern warehouse using Medallion layers</li>
<li><strong>ETL Pipelines:</strong> Extract, transform and load application data</li>
<li><strong>Data Modeling:</strong> Fact and dimension tables for analytics</li>
<li><strong>Analytics & Reporting:</strong> SQL queries and dashboards</li>
</ul>

<h3>Skills Demonstrated</h3>
<ul>
<li>SQL Development</li>
<li>Data Architecture</li>
<li>Data Engineering</li>
<li>ETL Pipeline Development</li>
<li>Data Modeling</li>
<li>Data Analytics</li>
</ul>
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
<h2>Tools Used</h2>
<table>
<tr><th>Tool</th><th>Purpose</th></tr>
<tr><td>SQL Server</td><td>Data warehouse database</td></tr>
<tr><td>DBeaver / SSMS</td><td>Database management</td></tr>
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

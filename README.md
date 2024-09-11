<h1 align="center">Data Analysis on Sales Insights Using Tableau & SQL  
<a href="https://public.tableau.com/app/profile/mrankitgupta" target="_blank" rel="noreferrer">  
<img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/a768d6bf0a001f03327578ae12f8867e4056cbaf/tableau-software.svg" alt="tableau" width="55" height="40"/>  
</a>  
</h1>

**A comprehensive data analysis project focused on sales insights for an India-based hardware company. Leveraging SQL for ETL processes and Tableau for advanced visualization, this project uncovers key metrics and provides data-driven business recommendations.**

---

## Project Overview 📝

This project explores the sales performance of an India-based hardware company, using SQL for data extraction and transformation, and Tableau for visualization. The objective is to provide insights into various parameters affecting company performance, including revenue trends, customer behavior, product profitability, and market segmentation.

### Key Features:
- Developed ETL pipelines using SQL to transform raw, unstructured data into a structured format.
- Built a star schema for efficient reporting and analysis in Tableau.
- Created dynamic Tableau dashboards to visualize sales data, enabling stakeholders to make informed, data-driven decisions.

---

## Technologies Used 💻

- **SQL (MySQL, SQL Server)**  
  <a href="https://www.mysql.com/" target="_blank">  
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="35" height="20"/>  
  </a>  
  <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer">  
  <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="sql-server" width="28" height="22"/>  
  </a>

- **Tableau**  
  <a href="https://public.tableau.com/app/profile/mrankitgupta" target="_blank" rel="noreferrer">  
  <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/a768d6bf0a001f03327578ae12f8867e4056cbaf/tableau-software.svg" alt="tableau" width="25" height="25"/>  
  </a>

- **Excel**  
  <a href="https://coursera.org/share/064db4645159df788ad0b31abebf1556" target="_blank" rel="noreferrer">  
  <img src="https://raw.githubusercontent.com/mrankitgupta/66DaysOfData/60139fb461ef56a19afd68ea4094f6069f27ce49/icons8-microsoft-excel%20(1).svg" alt="excel" width="25" height="25"/>  
  </a>

---

## Problem Statements 🧐

1. **Revenue Breakdown**: Analyze revenue distribution across different cities and regions.
2. **Time-Based Analysis**: Investigate sales trends over years and months.
3. **Customer Segmentation**: Identify the top 5 customers by revenue and sales quantity.
4. **Product Insights**: Discover the top 5 products by revenue generation.
5. **Profitability**: Evaluate net profit and profit margin across different markets.

---

## Project Goals 🎯

### Objective:
To provide actionable sales insights that support strategic decision-making, while reducing manual data handling by automating reporting processes.

### Stakeholders:
- Sales Director
- IT Team
- Customer Service Team
- Data & Analytics Team

### Expected Outcomes:
- Automated dashboards offering real-time insights into sales performance.
- A 10% improvement in decision-making efficiency, with a 20% reduction in manual data processing for sales analysts.

---

## Approach & Methodology 📊

1. **ETL Process**:  
   - Data extraction from unstructured sources using SQL.  
   - Data transformation, cleaning, and loading into a star schema for reporting in Tableau.

2. **Visualization**:  
   - Developed interactive Tableau dashboards to track key metrics such as revenue, sales trends, customer behavior, and product performance.

---

## Setup Instructions ⚙️

1. Download the database file:  
   - **[SQL Dump](https://github.com/mrankitgupta/Sales-Insights-Data-Analysis-using-Tableau-and-SQL/blob/main/Databases/db_dump.sql)**  
   - **[Excel Dump](https://github.com/mrankitgupta/Sales-Insights-Data-Analysis-using-Tableau-and-SQL/blob/main/Databases/db_dump.xlsx)**

2. Import the data into **MySQL** or **SQL Server** and perform ETL processes if necessary.

3. Download **Tableau Public** or **Tableau Desktop** to build your visualizations.  
   - [Download Tableau Public](https://www.tableau.com/products/public/download)  
   - [Download Tableau Desktop](https://www.tableau.com/products/desktop/download)

4. Connect Tableau to the SQL database or Excel data source.

5. Save your Tableau file as `.twb` or `.twbx`.

---

## SQL Data Queries 🛠️

- Show all customer records:  
  `SELECT * FROM customers;`

- Total number of customers:  
  `SELECT count(*) FROM customers;`

- Transactions in the Chennai market:  
  `SELECT * FROM transactions WHERE market_code='Mark001';`

- Product codes sold in Chennai:  
  `SELECT DISTINCT product_code FROM transactions WHERE market_code='Mark001';`

- Total revenue in 2020:  
  `SELECT SUM(sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date WHERE date.year=2020;`

---

## Tableau Dashboards 📈

### Revenue Analysis:
<p align="center">  
<a href="https://public.tableau.com/views/SalesInsights-DataAnalysisProject/Dashboard-RevenueAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link">  
<img width="100%" src="https://github.com/mrankitgupta/Sales-Insights-Data-Analysis-using-Tableau-and-SQL/blob/main/images/Tableau%20Dashbpard%20Revenue%20Analysis.png" />  
</a>  
</p>

### Profit Analysis:
<p align="center">  
<a href="https://public.tableau.com/views/SalesInsights-DataAnalysisProject/Dashboard-ProfitAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link">  
<img width="100%" src="https://github.com/mrankitgupta/Sales-Insights-Data-Analysis-using-Tableau-and-SQL/blob/main/images/Tableau%20Dashbpard%20Profit%20Analysis.png" />  
</a>  
</p>

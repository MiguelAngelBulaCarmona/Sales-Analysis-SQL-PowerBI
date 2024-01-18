# SalesAnalysis_SQL_PowerBI

## Overview
This project involves the creation of visual dashboards in Power BI for enhanced sales reporting. The goal is to provide a dynamic and interactive way of viewing internet sales data, allowing sales managers and representatives to track sales performance in relation to various parameters like products, customers, and budget comparisons.

### Business Demand Overview
- **Value of Change:** Transition to visual dashboards for better tracking and analysis of internet sales.
- **Necessary Systems:** Power BI, SQL
- **Other Relevant Info:** Budgets for 2021 are provided in Excel format.

### User Stories
1. **Sales Manager:** Requires a dashboard overview of internet sales to track which customers and products sell the best.
   - Acceptance Criteria: A Power BI dashboard updating data daily.
2. **Sales Representative:** Needs a detailed overview of Internet Sales per Customer for effective follow-up.
   - Acceptance Criteria: A Power BI dashboard with customer-wise data filtering.
3. **Sales Representative:** Wants a detailed view of Internet Sales per Product to identify top-selling items.
   - Acceptance Criteria: A Power BI dashboard with product-wise data filtering.
4. **Sales Manager:** Seeks a dashboard overview to compare sales over time against the budget.
   - Acceptance Criteria: A Power BI dashboard with graphs and KPIs for budget comparison.


### Setup
- **Requirements:** SQL Server (SQL Express), Power BI Desktop.
- **Data Sources:** Backup Data Warehouse (DW) data and Lightweight (LT) data. Instructions to obtain and restore data are available [here](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).
- **Data Preparation:** Use [this SQL script](https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql) to update Data Warehouse data.

### Data Analysis Steps
1. **Understand Data Structure:** Learn the difference between FACT tables and Dimension tables in the data warehouse.
2. **Identify Relevant Data:** Select tables and columns relevant to the business request.
3. **Clean and Transform Data:** Use T-SQL for data preparation, including renaming, combining columns, and more.

### Dashboard Creation in Power BI
- Load and organize data.
- Create a data model by connecting relevant tables.
- Design the dashboard with various visual elements like pie charts, bar charts, line charts, map graphs, and top 10 graphs.
- Implement custom visual styles and gradient bar chart colors.
- Include details for customers and pivot tables.
- 
## About the Author

- **Miguel Angel Bula Carmona**
- miguelangelbula.com
- www.linkedin.com/in/miguel-angel-bula-carmona-387913273

## Contact

email: mbula@unal.edu.co

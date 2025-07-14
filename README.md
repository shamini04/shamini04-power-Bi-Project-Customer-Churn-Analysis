## Bank Churn Analysis Dashboard – Power BI
## **Project Overview:**
This project presents a detailed analysis of customer churn for a banking institution using Power BI. The dashboard is designed to help business users identify churn trends, understand customer behavior, and take preventive action to reduce future attrition.
## dataset Used 
-<a href="https://github.com/Thirisha255/power-Bi-Project-Customer-Churn-Analysis/blob/main/bank%20churn%20dataset.csv">Dataset</a>
##  Data Modeling & Preparation:
- Used one central Fact Table (Bank Churn Data) and multiple Dimension Tables (Customer Info, Geography, Gender, Credit, etc.).
- Created a custom Calendar Table using DAX to enable time-based analysis.
- Implemented Star Schema with one-to-many relationships between the calendar/dimension tables and the fact table.
- Added a calculated column for Credit Type Classification (Excellent, Very Good, Good, Fair, Poor) based on credit scores.
## Key KPIs:
- Total Customers (distinct count)
- Active Customers
- Inactive Customers
- Credit Card Holders
- Non-Credit Card Holders
- Exit Customers
- Retained Customers
- Each KPI is dynamically calculated and displayed in the report header for quick business insights.
##  Visual Insights:
- Bar Chart: Total customers by year segmented by Active and Inactive status.
- Line Chart: Monthly trend of Exit Customers vs Previous Month Customers.
- Donut Chart: Gender-wise distribution of Exit Customers.
- Bar Chart: Exit Customers by Credit Type.
- Pie Chart: Exit Customers by Category (Credit Card Holders vs Non-Holders).
- Table View: Year-wise Churn % calculated using a custom measure (Churn % = Exit Customers / Total Customers).
## Interactivity & Filters:
**Dynamic slicers for:**
- Year
- Month Name
- Geography Location
- Active Category
- Exit Category
- Gender Category
These filters enable users to drill down into churn data by various customer attributes.
##  Tools & Skills Used:
- Power BI Desktop
- Power Query for ETL
- DAX for Calculated Columns & Measures
- Star Schema Modeling
- Time Intelligence
- Data Visualization
## Dashboard Image
-<a href="https://github.com/Thirisha255/power-Bi-Project-Customer-Churn-Analysis/commit/9099058f4ac4d00a392cd6206aa2fa2d531616fb">Dashboard image</a>
## Outcome:
This dashboard allows stakeholders to monitor churn patterns, analyze customer demographics, and design strategies to retain valuable customers based on historical trends and predictive insights.

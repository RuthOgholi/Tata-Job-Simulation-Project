# Online Retail Store Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Used](#dataset-used)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analytics](#data-analytics)
- [Data Visualization](#data-visualization)
- [Results of Findings](#results-of-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
---

This data analysis project aims to provide insights into the sales performance of an online retail store for a period of one year i.e 2011. By analyzing various aspects of the sales data, I sought to identify trends, make data driven recommendations, and gain a deeper understanding of the store’s lucrative opportunities that can be leveraged for expansion.

### Dataset Used
---

Online Retail Store dataset: The dataset used for this analysis is the ‘Online Retail .xlsx’ file, containing detailed information about each sale by the company.
- [Dataset](https://github.com/RuthOgholi/Sales-Analysis-Project/blob/ac0e6ccc67b578e9db54fec09703ead3b55f627e/Online%20Retail%20Data%20Set.xlsx)

### Data Source
---
The ‘Online Retail .xlsx’ dataset was provided by [Tata Group](https://en.wikipedia.org/wiki/Tata_Group) as part of my virtual internship.


### Tools
---

- Excel - Data Cleaning/Analysis
  - [Download here](https://microsoft.com)
- Power BI - Data Manipulation/Creating Reports
   - [Download here](https://apps.microsoft.com/detail/9ntxr16hnw1t?launch=true&mode=full&hl=en-us&gl=ng&ocid=bingwebsearch)



### Data Cleaning/Preparation
---
  In the initial data preparation phase, I performed the following task:
- Data loading and inspection.

To ensure my analysis is accurate and reliable I did the following:
1. Removed null values in ‘CustomerID’ field.
2. Identified and removed extreme outliers in ‘Quantity’ and ‘UnitPrice’ fields that could skew my analysis.
3. Formatted ‘InvoiceDate’, ‘Date’, ‘InvoiceNo’, ‘StockCode’, and ‘CustomerID’ fields.
4. Filtered data for 2011 where required.
5. Created a ‘Revenue’ column by multiplying ‘Quantity’ by ‘UnitPrice’.
6. Excluded rows where country was United Kingdom for questions requiring non-UK insights.

### Exploratory Data Analysis
---

EDA involved exploring the sales data to answer the following key questions:

- What is the monthly trend of revenue?
- Which months have faced the biggest increase? 
- Is there a seasonality in sales?
- Apart from the United Kingdom, which region is generating the highest revenue, and which is generating the lowest?
- Who are the top 10 customers and how much do they contribute to the total revenue? Is the business dependent on these customers?
- Apart from the UK, which regions have the greatest demand for products?

### Data Analytics
---

To answer the questions above I did the following:

1. Created a calculated column for ‘Revenue’ using Power Query editor in Excel.
2. Converted the dataset to a table in Excel.
3. Inserted a Pivot Table to summarize the data and answer each question.
4. Manipulated the data in power query editor in Power BI
5. Loaded the data to Power BI for visualization of my findings.

### Data Visualization
---

To prepare my dataset for visualization I did the following:
- Loaded the dataset on power query editor in Power BI
- Formatted ‘InvoiceDate’, ‘Date’, ‘InvoiceNo’, ‘StockCode’, and ‘CustomerID’ fields.
- Loaded the manipulated dataset into Power BI.
- In Power BI I filtered the charts axes for top 10 countries by revenue generated and quantity demanded excluding United Kingdom.
- I filtered the charts axes for top 10 customers by revenue generated

To visualize my analysis I used the following:
- An area chart to show monthly revenue for January to December 2011.
- A Side-by-side bar chart to show the top 10 countries by revenue and quantity demanded excluding United Kingdom.
- A vertical bar chart to show the lop 10 customers by the revenue generated.
- A treemap chart showing the quantity demanded by each country excluding United Kingdom.

Here are the visuals:
- [Power BI Visuals](https://github.com/RuthOgholi/Sales-Analysis-Project/blob/main/Online%20Retail%20Data%20Visuals.pbix)


### Results of Findings
---

The analysis results are summarized as follows:

- The revenue in the first 8 months is fairly constant as the average revenue generated for these 8 months is around $685k. The increase in revenue starts in the month of September, where the revenue increased by 40% over previous month. This trend continues till the month of November. This shows that store sales are impacted by seasonality which usually occurs in the last 4 months of the year.
- Apart from the UK, countries such as the Netherlands, Ireland, Germany and France have high volume of unit bought and revenue generated. Most of the revenue are only in European region with few in the American region. 
- There is not much of a difference between the purchases made by the top 10 customers. The highest revenue generating customer only purchased 17% more than the 2nd highest which shows that the business is not relying only on a few customers
to generate the revenue.
- Apart from the UK, countries such as the Netherlands, Ireland, Germany and France are generating high revenue.


### Recommendations
---

Based on the analysis, I recommend the following:

- Seeing that sales increase in the last 4 months of the year, the CEO should plan and execute campaigns for such months especially November.
- The CEO should also expand operations in high-demand regions like the Netherlands, Ireland, Germany and France.
- The CMO should target marketing efforts in top-performing regions like the Netherlands, Ireland, Germany and France
- The CMO should develop customer retention strategies for high-revenue customers.
- The CMO should align marketing campaigns with seasonal trends to drive more revenue.

 ### Limitations
 ---

1. I had to remove all null values from ‘CustomerID’ field because they would affect the accuracy of my conclusion from the analysis.
2. I excluded the UK where it was required for me to do so.
3. I removed the data for December 2010 because it was irrelevant to my analysis.
4. I created calculated column for ‘Revenue’, to make my analysis easier.
5. I removed extreme outliers in ‘Quantity’ and ‘UnitPrice’ fields that could skew my analysis.

### References
---

- Chat GPT (https://chatgpt.com/?ref=dotcom)
- 27 Business Success Metrics You Should Be Tracking (https://asana.com/resources/success-metrics-examples)
- How to Choose the Right Chart for Data Visualization (https://www.analyticsvidhya.com/blog/2021/09/how-to-choose-the-right-chart-for-data-visualization/)
- How to Choose the Right Chart for Your Data (https://infogram.com/blog/choose-the-right-chart/)
- How to Choose the Right Data Visualization (https://www.atlassian.com/data/charts/how-to-choose-data-visualization)
- Which Type of Chart or Graph is Right for You? (https://www.tableau.com/learn/whitepapers/which-chart-or-graph-is-right-for-you)

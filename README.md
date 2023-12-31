# Maji Ndogo Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Recommendations](#recommendations)

### Project Overview

This data analysis aims to provide insights into the sales performance of an ecommerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations and gain deep understanding of the company's performance.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed information about each sale made by the company.

### Tools

- Google sheets - Data Cleaning [Download here](https://microsoft.com)
- Sql server - Data Analysis
- PowerBI - Creating a report

### Data Cleaning/Preparation

In the initial preparation phase, we performed the following tasks:
1. Data loading and inspection.
   - Imported dataset and split columns on semicolon.
3. Handling missing values.
   ```sheets
   #count all rows to identify missing values and solved by filter and splitting columns
   =COUNTA(A2:P2)
   ```
5. Data cleaning and formatting.
   - Added new columns such as, year difference grouped by countries, annual rates of exchange by area and region, and rounded national population.

### Exploratory Data Analysis

EDA involved exploring the md_water_services data to answer key questions, such as:

- What type of water sources need to be improved and where?
- Who are we doing this for and where are they?
- What do we need to do, and where do we need to do it?
- What will this cost?
- How far is the project?
- How much money has been spent so far?
- Where to cut costs.

### Data Analysis

Include some interesting code/features worked with

```sql
Select * from table1
where cond - 2;
```

### Results/Findings

The analysis results are summarized as follows:
- The company's sales have been steadily increasing over the past year, with a noticecable peak during the holiday season.
- Product Category A is the best-performing category in terms of sales and revenue.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusion from the analysis.

###

1. SQL for Businesses by werty.
2. [Stack Overflow](https://google.com)

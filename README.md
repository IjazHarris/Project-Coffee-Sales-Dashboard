# Project: Coffee Sales Interactive Dashboard

This project is an end-to-end Excel data analysis and dashboarding project focused on analyzing coffee sales data. The dataset simulates a retail coffee business and demonstrates how Excel can be used for data cleaning, transformation, analysis, and visualization without external BI tools.

<img width="1232" alt="image" src="https://github.com/user-attachments/assets/257fb4b7-1caf-4ef0-96cb-bde97680dc27" />

## 1. Data Used:
a. Data set extracted from Kaggle

b.Data Cleaning & Analysis: Excel

c.Data Visualization: Excel

## Objectives

Objectives

a. The main objectives of this project are to:

b. Consolidate raw sales, customer, and product data into a structured format

c. Analyze total sales performance over time

d. Identify top-performing customers and countries

e. Build a clear, interactive Excel dashboard for business decision-making

## Analysis & Dashboard

a. The Excel dashboard provides a high-level business view, including:

b. Total Sales Over Time – trend analysis by date

c. Sales by Country – geographic performance comparison

d. Top 5 Customers – highest revenue contributors

e. Product Performance – breakdown by coffee type, roast type, and size

f. Interactive slicers allow users to filter by:

g. Date range

h. Coffee type

i. Roast type

## Tools Used

a. Pivot Tables & Pivot Charts

b. Excel formulas and calculated fields

c. Dashboard design and slicers

## Findings

a. The top 5 customers are (desc order) : Allis Wilmore, Brenn Dundredge, Terrin Farra, Nealson Cuttler, Don Flintiff

b. Over the four-year period, the United States consistently contributed to sales across all coffee types. This trend may be influenced by factors such as population size, coffee culture, and consumption habits. Overall, all three countries show a stronger preference for dark roast coffee compared to other types. Based on these findings, expanding the business in the U.S. market would likely be the most lucrative option.

## Notable formula

```excel
=INDEX(products!$A$1:$G$49,MATCH(orders!$D3,products!$A$1:$A$49,0),MATCH(orders!I$1,products!$A$1:$G$1,0)
```

This formula is used to dynamically retrieve product-related information (such as coffee type, roast type, size, or price) from the Products sheet into the Orders sheet




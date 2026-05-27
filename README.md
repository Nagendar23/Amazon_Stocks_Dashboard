# AMAZON STOCK ANALYSIS DASHBOARD

## Overview

The **Amazon Stock Analysis Dashboard** is an interactive Excel dashboard built to analyze Amazon (AMZN) historical stock performance using Pivot Tables, Pivot Charts, and Slicers.

The dashboard enables users to explore:
- Stock price trends
- Trading volume behavior
- Monthly and yearly performance
- Open, High, Low, and Close price comparisons
- Adjusted closing price analysis

---

# Dashboard Features

## KPI Cards
The dashboard displays key stock metrics:
- Average High Price
- Average Low Price
- Average Open Price
- Average Close Price

---

## Interactive Filters
Users can dynamically filter data using slicers:
- Year
- Month
- Day

---

## Visualizations Included

### 1. Volume Over Time
- Pie chart showing trading volume distribution across weekdays.

### 2. Open V/S High
- Clustered bar chart comparing average Open and High prices by weekday.

### 3. Trading Value Analysis
- Horizontal bar chart showing trading activity across months.

### 4. Monthly Avg Adj Close Price
- Column chart showing average adjusted closing prices by month.

### 5. High V/S Low By Day
- Horizontal comparison chart of High and Low prices across weekdays.

### 6. Yearly Trends in Adj Close
- Line chart visualizing long-term growth in adjusted closing prices.

---

# Dataset Information

## Dataset Source
Amazon Historical Stock Dataset (AMZN)

## Columns Used

| Column | Description |
|---|---|
| Date | Trading Date |
| Open | Opening Price |
| High | Highest Price |
| Low | Lowest Price |
| Close | Closing Price |
| Adj Close | Adjusted Closing Price |
| Volume | Number of Shares Traded |

---

# Derived Columns

Additional fields created for analysis:
- Year
- Month Name
- Day Name

---

# Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Slicers
- Data Cleaning Techniques
- Conditional Formatting
- Excel Table Structures

---

# Data Cleaning Process

The original dataset contained:
- Mixed datatypes
- Text-formatted numeric values
- Aggregation errors
- Pivot calculation issues

## Cleaning Steps Performed
1. Converted text values into numeric format
2. Removed invalid records and errors
3. Standardized date formatting
4. Created helper columns
5. Refreshed Pivot Tables after cleanup
6. Structured data into Excel Tables

---

# Business Insights

- Amazon stock experienced significant growth after 2015.
- Trading activity remains relatively balanced across weekdays.
- Adjusted closing prices show strong upward momentum from 2018 onward.
- Monthly price movement remains moderately stable.

---

# Challenges Faced

- `#DIV/0!` errors in Pivot Tables
- Mixed numeric and text datatypes
- Excel table expansion issues
- Formula dependency problems
- Pivot cache inconsistencies

---

# Future Improvements

Potential enhancements:
- Candlestick Charts
- Moving Average Analysis
- Volatility Indicators
- Real-Time API Integration
- Power BI Dashboard Version
- Automated Data Refresh using Power Query

---

# Learning Outcomes

This project helped improve skills in:
- Financial Data Analysis
- Excel Dashboard Development
- Data Cleaning
- Data Visualization
- Pivot Table Analysis
- Interactive Reporting

---

# Conclusion

The Amazon Stock Analysis Dashboard provides an interactive and structured approach to analyzing historical Amazon stock performance using Microsoft Excel. The project demonstrates practical implementation of Excel-based business intelligence and financial analytics techniques.

---

# Superstore Sales Dashboard

An interactive sales dashboard built from the Superstore dataset, made as part of the DEPI internship graduating projects (Group 2).

**Live dashboard:** https://g2-depi.github.io/Superstore-Project/

## Project Overview
The raw data was cleaned with Power Query, modeled as a star schema in Power BI, and then rebuilt as an interactive web dashboard with HTML, CSS and JavaScript.

## Data Cleaning (Power Query)
- Removed duplicates
- Fixed data types: Order Date and Ship Date from text to Date, Postal Code to Text, Sales to a decimal
- Handled nulls
- Split Customer Name into First Name and Last Name
- Merged City and State into one Location column

## Key KPIs
| KPI | Value |
|---|---|
| Total Sales | $2.26M |
| Total Orders | 4,922 |
| Customers | 793 |
| Average Order Value | $459 |
| YoY Growth (2018 vs 2017) | +20.3% |

## Key Insights
- Sales dipped 4.2% in 2016, then grew 30.6% in 2017 and 20.3% in 2018
- Sales peak in September, November and December
- Technology leads with 36.6% of sales, then Furniture (32.2%) and Office Supplies (31.2%)
- West (31.4%) and East (29.6%) are the top regions
- Consumer is the largest segment at 50.8%

## Dashboard Features
- Four pages: Overview, Sales, Orders and Customers
- Filters for Year, Region, Category and Segment
- Click any bar, column or chart legend to filter
- Works on desktop and mobile, in light and dark mode

## Tools
Power Query, Power BI, DAX, HTML, CSS, JavaScript, GitHub Pages

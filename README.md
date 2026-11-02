# Sales Performance Analysis

An end-to-end analysis of 1,000 sales orders (January 2023 to January 2024): Excel pivot tables, an interactive web dashboard and a short case study.

**Live dashboard:** https://harshalrayte.github.io/sales-analysis-dashboard-Public/

![Dashboard](dashboard.png)

> The dataset is a sample used for practice. Sales amount is treated as revenue.

## Business problem

Which regions, sales reps and product categories drive revenue, and does discounting actually increase sales?

## Data

1,000 orders with date, region, sales rep, product category, sales channel, customer type, payment method, quantity, discount and sales amount.

## Approach

1. Cleaned the data and turned it into an Excel table. Added a discount band column (0-10%, 10-20%, 20-30%).
2. Built 6 pivot tables: region by category, sales rep by region, monthly trend by channel, customer value, discount impact and payment method.
3. Added KPI formulas, charts and slicers so every pivot can be filtered by region, customer type and channel.
4. Wrote the findings and recommendations, then rebuilt the analysis as a web dashboard.

## KPIs

| KPI | Value |
|---|---|
| Total sales | 50,19,265 |
| Orders | 1,000 |
| Average order value | 5,019 |
| Units sold | 25,355 |
| Average discount | 15.2% |

## Key findings

- **Regions:** North leads (13,69,613). South trails by about 16% and has fewer orders (226 against 267).
- **Sales reps:** David and Bob lead. Charlie is about 25% lower, weak in East and South but strong in North.
- **Seasonality:** January, October and November are strong. February and September are about 22% below January.
- **Discounts:** Average order value moves only from 4,949 to 5,139 as discounts rise. In Electronics it falls from 5,256 to 4,721 and orders drop from 101 to 61.
- **Customers:** New and Returning customers contribute almost equally, but Returning customers place about 16% larger Electronics orders.

## Recommendations

1. Support South and Charlie's East and South territories.
2. Plan campaigns for February and September.
3. Stop deep discounts on Electronics and test them on Clothing and Food.

## Limitations

Profit is not analysed because unit price and unit cost do not reconcile with sales amount in this dataset. January 2024 has only 3 orders, so it is not used to read the trend.

## Repository

```
   index.html                 interactive dashboard (hosted with GitHub Pages)
   sales_analysis.xlsx        pivot tables, KPI sheet, charts, slicers, insights
   sales_data.csv             dataset
```

## Tools

Excel (pivot tables, slicers, formulas), Python (pandas) and Chart.js.

## Author

Harshal Rayte, MBA (Finance), aspiring Business Analyst.

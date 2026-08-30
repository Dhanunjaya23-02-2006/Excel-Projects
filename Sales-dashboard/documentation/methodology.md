# Project Methodology

## 1. Data Collection

The project uses a Sample Superstore retail dataset stored in the `dataset` folder.

## 2. Data Cleaning

Power Query is used to:

- Check column names
- Set appropriate data types
- Clean date fields
- Validate numeric columns
- Check blanks and errors
- Review duplicates
- Prepare a clean analysis table

The cleaned output is loaded into Excel as `Clean_Data`.

## 3. Data Preparation

The cleaned dataset is maintained as an Excel Table and used as the source for analysis.

## 4. Exploratory Analysis

Pivot Tables are created for:

- Monthly sales
- Category sales
- Sub-category sales
- Top products
- Regional sales
- Regional profit
- Customer segments
- Shipping modes
- Top customers
- Negative-profit products

## 5. KPI Development

Five KPIs are calculated:

1. Total Sales
2. Total Profit
3. Total Orders
4. Average Order Value
5. Profit Margin %

## 6. Visualization

Recommended charts:

- Line → monthly trends
- Clustered Column → category/region comparisons
- Clustered Bar → product/sub-category rankings
- Donut → simple composition/share

## 7. Interactivity

Slicers and a Timeline filter the relevant Pivot Tables and charts by:

- Region
- Category
- Segment
- Order Date

## 8. Business Interpretation

The dashboard is used to identify revenue leaders, profit leaders, loss-making products, customer opportunities, regional differences, and time trends.

## 9. Quality Checklist

- [ ] Power Query data refreshed
- [ ] Data types checked
- [ ] Total Sales validated
- [ ] Total Profit validated
- [ ] Total Orders uses unique Order IDs
- [ ] AOV uses Sales ÷ Orders
- [ ] Profit Margin uses Profit ÷ Sales
- [ ] Charts have clear titles
- [ ] Slicers work
- [ ] Timeline works
- [ ] KPI cards update correctly
- [ ] Insights match workbook results

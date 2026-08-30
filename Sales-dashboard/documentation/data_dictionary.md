# Data Dictionary

Verify the exact fields in the dataset before final submission.

| Field | Description | Analytical Use |
|---|---|---|
| Row ID | Unique row identifier | Record tracking |
| Order ID | Order identifier | Unique order counting |
| Order Date | Date order was placed | Time analysis |
| Ship Date | Date order was shipped | Shipping analysis |
| Ship Mode | Shipping method | Logistics analysis |
| Customer ID | Customer identifier | Customer analysis |
| Customer Name | Customer name | Customer ranking |
| Segment | Customer segment | Segment analysis |
| Country | Country | Geographic analysis |
| City | City | Geographic analysis |
| State | State | Geographic analysis |
| Postal Code | Postal code | Geographic analysis |
| Region | Sales region | Regional comparison |
| Product ID | Product identifier | Product analysis |
| Category | Product category | Category analysis |
| Sub-Category | Product sub-category | Product analysis |
| Product Name | Product name | Product ranking |
| Sales | Sales/revenue value | Revenue KPIs |
| Quantity | Units sold | Volume analysis |
| Discount | Discount applied | Pricing analysis |
| Profit | Profit value | Profitability analysis |

## Measures

**Total Orders:** count of unique Order IDs.

**Average Order Value:**
```text
Total Sales ÷ Unique Orders
```

**Profit Margin:**
```text
Total Profit ÷ Total Sales × 100
```

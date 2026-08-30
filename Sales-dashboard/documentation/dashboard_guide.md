# Dashboard Guide

## Recommended Layout

```text
SALES PERFORMANCE DASHBOARD
Retail Sales Analytics | 2014–2016

[Region] [Category] [Segment] [Order Date Timeline]

[Total Sales] [Total Profit] [Total Orders] [AOV] [Profit Margin]

[Monthly Sales Trend]     [Sales by Category]
[Sales by Sub-Category]   [Top 10 Products]
[Sales by Region]         [Profit by Region]
[Sales by Segment]        [Orders by Ship Mode]
```

## Chart Selection

| Analysis | Chart |
|---|---|
| Monthly Sales Trend | Line |
| Sales by Category | Clustered Column |
| Sales by Sub-Category | Clustered Bar |
| Top 10 Products | Clustered Bar |
| Sales by Region | Clustered Column |
| Profit by Region | Clustered Column |
| Sales by Segment | Donut |
| Orders by Ship Mode | Clustered Column |

## Design Guidelines

- Use a consistent font.
- Keep the background clean.
- Use one primary accent color and neutral supporting colors.
- Avoid 3-D charts.
- Avoid excessive borders.
- Keep chart titles consistent.
- Use readable number formats.
- Remove dashboard gridlines.
- Align KPI cards and charts.
- Keep slicers in one area.

## Testing

Test several filter combinations.

Example:

```text
Region = West
Category = Technology
Segment = Consumer
```

Confirm that KPIs and connected charts change.

Then clear all filters and confirm that the dashboard returns to the full dataset.


# Car Sales Analysis – India 2024
### Power BI Dashboard Project

---

## Objective
Analyze Indian car market performance in 2024 across brands, models, segments, and body types to identify sales trends, market leaders, and growth opportunities.

---

## Tools Used
- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Dataset Overview

| Field | Details |
|-------|---------|
| Records | 1,044 rows (87 models × 12 months) |
| Total Brands | 14 |
| Total Models | 87 |
| Time Period | January – December 2024 |
| Key Metric | Monthly Sales |
| Key Fields | Make, Model, Segment, Body Type, Monthly Sales |

---

## Data Model

Designed using a star schema for optimal Power BI performance.

- 1 Fact Table (FACT_Sales) containing all transactional records
- 4 Dimension Tables: DIM_Calendar, DIM_Brand, DIM_Segment, DIM_BodyType
- Monthly columns unpivoted using Power Query for time-series analysis
- All relationships: One-to-Many (Dimension to Fact)

---

## DAX Measures

**Core Metrics**
- Total Sales, Total Brands, Total Models
- Average Sales per Model

**Trend Analysis**
- MoM Change, Previous Month Sales
- Growing Models, Declining Models

**Ranking**
- Top Brand, Top Model, Top Segment, Top Quarter

---

## Key Insights

- Total sales reached 4 million units across 14 brands
- Maruti leads with 46.77% market share
- Punch is the top-selling model
- SUVs dominate body type distribution at 50.44% of total sales
- October is the peak sales month, driven by festive season demand
- Top 4 brands contribute nearly 80% of total market share
- S-Presso and Tucson recorded the highest sales decline

---

## Business Recommendations

- Focus corrective actions on consistently declining models
- Leverage festive season demand for targeted marketing campaigns
- Explore growth opportunities in the premium segment
- Monitor emerging EV adoption trends

---

## Files

- `Car_Sales_2024.pbix` — Power BI dashboard file
- `README.md` — Project documentation

---

## Author

**Eva Reji**
GitHub: github.com/EvaReji | LinkedIn: linkedin.com/in/eva-reji

## Hi, I'm Igor 👋

BI Developer with an analytics-engineering mindset and focus. I build end-to-end reporting on data models that hold up, and the part I care about most sits under the dashboard: the SQL and the modeling that a polished report tends to bury.

### Selected Projects 📁

1. **Olist delivery analytics - SQL warehouse and analysis**

End-to-end analytics engineering project on the Brazilian e-commerce dataset (~99k orders). Star schema warehouse in MySQL with seven analytical questions, each paired with a written business interpretation. Built to demonstrate the modeling and SQL patterns behind production analytics work.

Scope:
- Layered warehouse: raw → staging → marts, following dbt conventions
- Kimball star schema: 4 dimensions, 2 facts, degenerate dimensions, bridge resolution for customer identity
- Advanced window functions across all seven analyses: PERCENT_RANK, ROW_NUMBER, RANK, DENSE_RANK, rolling frames with RANGE INTERVAL
- Post-build validation layer (dbt tests equivalent in raw SQL) and per-analysis business findings

Tech: MySQL 8, window functions, recursive CTEs, star schema, Kimball, layered warehouse architecture

→ [github.com/ipiotrowski/delivery_bottleneck_analysis_sql](https://github.com/ipiotrowski/delivery_bottleneck_analysis_sql)

2. **Delivery bottleneck analysis - Power BI**

End-to-end Power BI analysis of where e-commerce orders lose time before they reach the customer.

Scope:
- broke the order lifecycle into fulfillment stages to pinpoint where delays start
- star-schema model with bridge tables, built for drill-through
- bottleneck severity logic written in DAX as a reusable semantic layer
- report pairs an executive overview with diagnostic drill-down

Tech: Power BI, Power Query (M), DAX, star schema, layered architecture

→ [github.com/ipiotrowski/delivery_bottleneck_analysis](https://github.com/ipiotrowski/delivery_bottleneck_analysis)

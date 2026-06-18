## Hi, I'm Igor 👋

BI Developer with an analytics-engineering mindset and focus. I build end-to-end reporting on data models that hold up, and the part I care about most sits under the dashboard: the SQL and the modeling that a polished report tends to bury.

### Selected Projects 📁

**Delivery bottleneck analysis (Power BI)**

End-to-end Power BI analysis of where e-commerce orders lose time before they reach the customer.

Scope:
- broke the order lifecycle into fulfillment stages to pinpoint where delays start
- star-schema model with bridge tables, built for drill-through
- bottleneck severity logic written in DAX as a reusable semantic layer
- report pairs an executive overview with diagnostic drill-down

→ [github.com/ipiotrowski/delivery_bottleneck_analysis](https://github.com/ipiotrowski/delivery_bottleneck_analysis)


**Delivery bottleneck analysis (SQL Rebuild)** *(in progress)*

The same problem, rebuilt from the ground up as a layered SQL pipeline in MySQL.

Scope:
- raw → staging → marts structure following dbt conventions
- window functions and CTEs for lead-time percentiles and stage gaps
- the focus here is the SQL and modeling underneath the report

→ [github.com/ipiotrowski/delivery_bottleneck_analysis_sql)](https://github.com/ipiotrowski/delivery_bottleneck_analysis_sql)

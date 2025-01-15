# Monthly_Performance_DeepDive
The dashboard is built on top of PnL Snowflake table {{ ref('fct_amazon_kpi_performance') }} combining also inventory, sales velocity and DOC data. 
This integration includes the computation of essential time-comparison metrics (Month-1, Month-2, Month-12, MoM, YoY, YTD).

Use-Cases of the report:
1. To provide monthly reviews, developments and trends on core commercial KPIs. 
2. To identify levers for growth/decline of countries, categories, and brands (MoM, YoY).
3. To delve into the ASIN level for outliers, top-performers, and individual PnLs.

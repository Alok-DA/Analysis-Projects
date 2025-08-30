# Supply Chain Analysis — Power BI Dashboard

**Live Report:** [Open in Power BI](https://app.powerbi.com/links/J6JBd534cK?ctid=ffde924e-11ca-44e9-8e06-63965bc300f6&pbi_source=linkShare)

## Problem statement
Operations and customer teams lacked a single, trustworthy view of delivery performance—On-Time (OT), In-Full (IF), OTIF, Fill Rates (LIFR/VORF), and delay patterns—spread across spreadsheets with no easy drill-down by product, customer, or city. The business needed target tracking and quick identification of late orders and root-cause hotspots.

## Solution
I built an interactive Power BI report that consolidates order lines, targets, and service metrics into an executive-ready view. It surfaces KPIs (OT, IF, OTIF, LIFR, VORF, Average Days of Delayed Delivery—ADDD), monthly/quarterly trends vs targets, and side-by-side Product/Customer insights with slicers (Customer, Product, Month, Week, Category, City) and conditional formatting to highlight gaps.

## AIMS Grid
- **Aim:** Enable data-driven decisions to improve OTIF and Fill Rates while reducing late deliveries.
- **Stakeholders:** Supply-chain leadership, logistics & dispatch teams, customer success, demand planning.
- **End Result:** Self-service pages for **Overview (OT/IF/OTIF vs Target & Trend)**, **Product Insights (LIFR/VORF by month)**, **Customer Insights (OT/IF/OTIF, orders, ADDD)**, and **City Split**.
- **Success Criteria:** Visible target gaps via conditional formatting, reduced average delay days (ADDD), and improved OTIF/LIFR month-on-month.

## Steps Followed in this project
1. Connected and profiled order-line data; aligned KPI definitions (OT, IF, OTIF, LIFR, VORF, ADDD) and targets.
2. Built Power Query transformations; standardized date logic for monthly/quarterly trend analysis.
3. Modeled relationships and authored DAX measures for OT/IF/OTIF, LIFR, VORF, **ADDD**, and monthly trends vs target.
4. Designed visuals: OT/IF/OTIF vs Target cards & trend, Product table with **LIFR% by Month / VORF% by Month**, Customer table with **Total Orders & ADDD**, and City split.
5. Applied conditional formatting to emphasize gaps to target; added slicers (Customer, Product, Month, Week, Category, City) for flexible analysis.

## Final result
- **Overview KPIs:** Aggregate performance surfaced for quick action (e.g., **OT ≈ 59% vs target 86%**; **OTIF ≈ 29% vs target 65.91%**; **IF ≈ 52.8% vs target 76.51%**; **VORF ≈ 96.6%**; **LIFR ≈ 65.9%**).
- **Delay Lens:** **ADDD ≈ 1.69**; **~9K** orders flagged as late; delay distribution shown from **–1** (early) to **3** days.
- **Product Insights:** Side-by-side **LIFR/VORF** by month with examples like *AM Milk 500* (**LIFR ~67.5%**, **VORF ~96.7%**).
- **Customer Insights:** OT/IF/OTIF with totals & ADDD—e.g., *Atlas Stores* (**OT ~71.8%**, **IF ~59.8%**, **OTIF ~39.6%**, **VORF ~97.6%**, **ADDD ~1.50**, **1,322** orders).
- **City Split:** Comparative view across **Ahmedabad**, **Surat**, **Vadodara** to spot regional performance differences.

---
*Supply Chain Insights*
![Supply Chain Insights](https://github.com/Alok-DA/Analysis-Projects/blob/main/powerbi-supply-chain-analysis/images/Supply-Chain-Analysis-Report.jpg)

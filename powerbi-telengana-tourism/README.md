# Telangana Tourism Performance — Power BI Dashboard

**Live Report:** [Open in Power BI](https://app.powerbi.com/links/CMuZnEmZ1Q?ctid=ffde924e-11ca-44e9-8e06-63965bc300f6&pbi_source=linkShare)

## Problem statement
Tourism leaders in Telangana lacked a unified, trustworthy view of district-wise performance—domestic vs. foreign footfall, revenue outlook, and seasonality—making it hard to prioritize investments and campaigns across 30 districts using scattered spreadsheets.

## Solution
I built an interactive Power BI report consolidating visitor and revenue signals into an executive-ready view. The model standardizes district attributes, calculates KPIs (e.g., total domestic/foreign visitors, CAGR by district, domestic-to-foreign ratio), and layers in seasonality and 2025 forecasts (Hyderabad focus) to drive timely, data-backed actions.

## AIMS Grid
- **Aim:** Enable data-driven allocation of tourism budgets and campaigns using district-level footfall, growth, and seasonality.  
- **Stakeholders:** State tourism department, district administrators, marketing & partner relations.  
- **End Result:** Self-service pages for Overview, District Growth (CAGR), Market Mix (Domestic/Foreign), Capacity Proxy (Population-to-Footfall), Forecasts (2025), and Seasonality (peak/low months).  
- **Success Criteria:** Clear visibility into top/bottom growth districts, visitor mix, forecasted demand, and campaign-worthy months.

## Steps Followed in this project
1. Connected source data and profiled district fields; validated totals (e.g., ~356.34M domestic, ~1.06M foreign visitors).  
2. Performed ETL in Power Query (data types, date logic, district standardization); created a star-style model for performant slicing.  
3. Authored DAX measures for total/YoY visitors, CAGR by district, domestic-to-foreign ratios, population-to-resident-footfall ratio, and forecast measures for Hyderabad 2025.  
4. Designed visuals: Top 10 domestic districts, top/bottom CAGR, visitor-mix ratios, population-to-footfall heat, 2025 revenue/visitor forecasts, and month-wise peak/low analysis for Hyderabad.  
5. Tuned interactions (drill-down, cross-filtering), added slicers (Year, District), and optimized with appropriate relationships and filters.

## Final result
- **Overview:** One-glance KPIs for total districts (30), domestic (~356.34M) and foreign (~1.06M) visitors with year/district slicers.  
- **District Growth:** Top 3 domestic CAGR districts (e.g., Mancherial, Warangal-Rural, Bhadradri Kothagudem) and bottom 3 (e.g., Warangal-Urban, Nalgonda, Karimnagar) to target interventions.  
- **Market Mix:** Districts with high vs. low domestic-to-foreign ratios (e.g., Nirmal/Jangaon/Adilabad vs. Mulugu/Warangal/Hyderabad) for segment-specific campaigns.  
- **Capacity Proxy:** Population-to-resident-footfall ratio highlights (e.g., Medak, Hyderabad, Nirmal) to pinpoint under/over-utilized destinations.  
- **Forecasts & Seasonality:** 2025 outlook for Hyderabad (visitors and revenue) and peak/low months across domestic/foreign/total to time promotions effectively.

## Dashboards / Screens
> Add screenshots to your repo (e.g., `/images/…`) and update the relative paths below.

- **Visitors and Top Districts**  
  ![Visitors and Top Districts](https://github.com/Alok-DA/Analysis-Projects/blob/main/powerbi-telengana-tourism/images/visitors-top-districts.jpg)

- **CAGR and Population-Footfall Ratio Dashboard**
  ![CAGR and Population-Footfall Ratio Dashboard](https://github.com/Alok-DA/Analysis-Projects/blob/main/powerbi-telengana-tourism/images/cagr-population-footfall.jpg)

- **Hyderabad: Revenue and Forecasts**  
  ![Hyderabad: Revenue and Forecasts](https://github.com/Alok-DA/Analysis-Projects/blob/main/powerbi-telengana-tourism/images/hyderabad-revenue-forecast.jpg)

- **Hyderabad: Peak vs Low Months**  
  ![Hyderabad: Peak vs Low Months](https://github.com/Alok-DA/Analysis-Projects/blob/main/powerbi-telengana-tourism/images/hyderabad-peak-low-months.jpg)

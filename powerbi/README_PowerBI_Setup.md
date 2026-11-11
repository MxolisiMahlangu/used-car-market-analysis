# Used Cars Power BI Starter Pack

## Files
- used_cars_powerbi.csv: Power BI-ready data with helper columns. The dataset file is supplied separately in the downloadable starter pack.
- Used_Cars_DAX_Measures.dax: DAX measures and an optional calculated column.
- Used_Cars_PowerBI_Theme.json: importable report theme.
- dashboard_preview.png: static layout preview, included in the downloadable starter pack.

## Build the report in Power BI Desktop
1. Home > Get data > Text/CSV > select used_cars_powerbi.csv.
2. In Power Query, confirm Price, Year, Kilometer, Length, Width, Height, Seating Capacity, Fuel Tank Capacity, Price_Lakh, Vehicle_Age_Years and Mileage_Lakh_KM are numeric. Keep missing specification values as null; do not replace them with zero.
3. Rename the imported table to Cars (or change the table name in the DAX).
4. Create the measures in Used_Cars_DAX_Measures.dax using Modeling > New measure.
5. View > Themes > Browse for themes > select Used_Cars_PowerBI_Theme.json.
6. Build the visuals using the recommended field mapping below.

## Recommended one-page report layout
- Header: Used Cars Market Overview
- KPI cards: Total Listings, Average Asking Price, Median Asking Price, Average Mileage (KM), Average Vehicle Age (Years)
- Bar chart: Top 10 Makes by Total Listings
- Column chart: Average Asking Price by Make (Top 10 by listings)
- Donut chart: Listings by Fuel Type
- Donut chart: Listings by Transmission
- Bar chart: Listings by Location (Top 10)
- Scatter chart: Kilometer (X), Price (Y), Make (Legend); use a sample or filter to avoid overplotting
- Slicers: Make, Year, Location, Fuel Type, Transmission, Owner, Seller Type

## Data interpretation notes
- The records are concentrated in Indian cities (e.g. Mumbai, Delhi, Pune); the price values are therefore treated as INR for display. Confirm the source currency before publishing.
- The maximum model year in the file is 2022. Vehicle_Age_Years is calculated against the current system year at data-preparation time. If the report is refreshed in later years, refresh the CSV or use the DAX measure Average Vehicle Age (Years) for a dynamic calculation.
- Missing values exist in some technical specification columns. Keep these blank unless a business-approved imputation rule exists.
- The dataset has no transaction date or sales status, so it supports listing/asking-price analysis, not actual sales revenue, sales growth over time, or units sold.

# Used Car Market Analysis | Power BI

## Project Introduction

This project explores a dataset of used-car advertisements to identify patterns in vehicle listings, asking prices, manufacturers, fuel types, transmission types and locations. It demonstrates an end-to-end business intelligence workflow using Microsoft Power BI, Power Query and DAX.

The goal is to turn raw vehicle-listing data into clear, interactive insights that can help users understand the composition and advertised-price patterns of the used-car market.

## Project Objectives

- Measure the volume of vehicle listings and the number of represented manufacturers.
- Identify the most frequently listed manufacturers and locations.
- Compare listings by fuel type and transmission.
- Examine average and median advertised prices.
- Build an interactive Power BI dashboard with KPI cards, charts and slicers.
- Communicate findings, limitations and opportunities for further analysis.

## Tools and Technologies

- **Microsoft Power BI** – data modelling and dashboard development
- **Power Query** – data cleaning and transformation
- **DAX** – measures and calculated metrics
- **CSV** – source dataset

## Dataset Overview

The supplied dataset contains approximately **2,059 vehicle listings**, covering:

- 33 manufacturers
- 1,050 vehicle models
- 77 locations
- Advertised vehicle prices and vehicle specifications

The locations and dataset context indicate an Indian used-car market. Prices are presented in Indian rupees (₹), with price summaries expressed in lakh (₹100,000), consistent with the dataset analysis.

## Analysis and Key Findings

### 1. Manufacturer Listings

Maruti Suzuki has the largest number of listings, at approximately **440**, followed by Hyundai with approximately **349**. These counts indicate strong representation of both manufacturers in this dataset.

### 2. Fuel Type

| Fuel type | Listings |
|---|---:|
| Diesel | 1,049 |
| Petrol | 942 |

Diesel listings slightly outnumber petrol listings in the dataset.

### 3. Transmission

| Transmission | Listings |
|---|---:|
| Manual | 1,133 |
| Automatic | 926 |

Manual vehicles account for the larger share of listings.

### 4. Location

Mumbai has the highest listing count, at approximately **342**, followed by Delhi with approximately **307**. These figures describe the dataset's listing distribution and should not be interpreted as total market size for either city.

### 5. Advertised Price

- **Average asking price:** approximately ₹17.03 lakh
- **Median asking price:** approximately ₹8.25 lakh

The average is substantially higher than the median. This suggests that a smaller number of high-priced listings may be pulling the average upward. The median is therefore useful alongside the average when describing a typical listing price.

## Dashboard Plan

The Power BI report is designed to include:

- KPI cards: total listings, average asking price, median asking price and manufacturer count
- Listings by manufacturer
- Listings by fuel type
- Listings by transmission
- Listings by location
- Asking-price distribution
- Slicers for relevant vehicle attributes and location

## Conclusion

The dataset is led by Maruti Suzuki and Hyundai listings. Diesel and manual vehicles appear more frequently than petrol and automatic vehicles, while Mumbai and Delhi are the two most represented locations. The difference between the average and median asking prices highlights the value of using robust summary statistics when analysing vehicle prices.

Power BI provides a practical way to combine these measures and dimensions into an interactive report. The project demonstrates data preparation, exploratory analysis, DAX measure development, visualisation and business communication.

## Limitations

- The data represents **advertised listings**, not verified completed sales.
- Asking prices are not confirmed final transaction prices.
- The analysis is descriptive and reflects only the records included in this dataset.
- Missing values in some technical specification fields may affect analyses that use those fields.
- No causal conclusions should be drawn from the observed differences.

## Skills Demonstrated

- Data cleaning and preparation
- Exploratory data analysis
- Data modelling
- DAX calculations and KPI development
- Data visualisation
- Insight generation and communication

## Repository Structure

The repository will contain the source dataset (where redistribution is permitted), Power BI report, supporting DAX measures and documentation.

## Author

**Mxolisi Mahlangu**  
Data Analytics Portfolio Project

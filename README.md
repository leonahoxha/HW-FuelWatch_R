# Fuel Watch

## Overview

This project analyzes fuel price data from various brands, regions, and specific areas within the Peel region in Australia. Using the “fuelw” dataset, it explores how fuel prices change over time and examines the number of data points available for different brands and regions. The analysis provides insights into fuel price dynamics and regional price differences.

The analysis was performed using **R** with visualizations and data manipulation handled via common R libraries.

## Data Sources

The primary dataset used:

1. **Fuel Price Data (fuelw):** A dataset containing information on fuel prices across various brands and regions in Australia.

## Key Sections

### 1. Visual Data Exploration

#### i. Brands

- **a. Bar Chart of Data Points:**
  - A bar chart displays the number of data points for each brand, ordered from the most to the least data points.
  - **Key Insight:** The top three brands with the most data points are BP, Ampol, and Coles Express, while BOC, Caltex Woolworths, and OTR have the least.

- **b. Line Chart of Average Prices:**
  - A line chart shows the average price changes of each brand over time, with distinct colors for each brand.
  - **Key Insight:** Average prices exhibit similar patterns, with significant changes during November to December 2022 and July to September 2023.

#### ii. Regions

- **a. Bar Chart of Data Points:**
  - A bar chart shows the number of data points for each region, ordered from the most to the least.
  - **Key Insight:** The top three regions with the most data points are Metro, South-West, and Peel, while Pilbara, Kimberley, and Gascoyne have the least.

- **b. Line Chart of Average Prices:**
  - A line chart displays average price changes across regions over time.
  - **Key Insight:** Regions exhibit similar price patterns, with Gascoyne having the highest average price compared to others.

#### iii. Areas in the Peel Region

- **a. Bar Chart of Data Points:**
  - A bar chart shows the number of data points for areas within the Peel region.
  - **Key Insight:** Mandurah has the most data points (over 6,000), while Waroona has the least (just over 1,000).

- **b. Line Chart of Average Prices:**
  - A line chart illustrates how average prices changed over time for areas in Peel.
  - **Key Insight:** Average prices for areas in Peel follow similar patterns, with Mandurah having the highest average price.

#### iv. Petrol Stations in Murray (Peel Region)

- A graphic analyzes how average prices changed at petrol stations in the Murray area over time.
- **Key Insight:** Most petrol stations show similar price trends, with Canal Shop petrol station prices fixed at 199 for the past year.

### 2. Different Patterns of Price Dynamics

- The analysis identifies three changing patterns in average fuel prices:
  1. A decrease in prices during November to December 2022.
  2. A sudden increase in April 2023, followed by a decrease.
  3. A significant price increase in July 2023, peaking in September 2023.

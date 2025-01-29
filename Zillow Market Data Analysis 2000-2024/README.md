# Zillow 3-Bedroom Insights Dashboard

## Introduction☀️

The **Zillow 3-Bedroom Insights Dashboard** provides a comprehensive analysis of housing price trends, affordability, and growth across various states in the United States. This project utilizes a dataset containing monthly 3-bedroom housing prices from January 2000 to December 2024, offering valuable insights into housing market trends. The dashboard is designed to highlight key metrics such as the states with the highest growth, affordability rankings, and price distributions, making it an excellent portfolio project to demonstrate skills in data cleaning, analysis, and visualization.

The project encompasses a wide range of processes, from  data preparation to creating visually appealing and interactive Excel-based visuals. It aims to provide actionable insights for potential users, including real estate analysts, buyers, and policymakers.

---

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Data Preparation](#data-preparation)
   - [Initial Dataset Challenges](#initial-dataset-challenges)
   - [Data Cleaning Process](#data-cleaning-process)
3. [Dashboard Features](#dashboard-features)
   - [Key Metrics](#key-metrics)
   - [Visuals and Insights](#visuals-and-insights)
4. [Technical Implementation](#technical-implementation)
   - [Excel Techniques](#excel-techniques)
5. [Insights Derived](#insights-derived)
6. [Future Improvements](#future-improvements)

---

## Dataset Overview

The dataset contains monthly housing prices for 3-bedroom homes across 51 states in the United States from January 2000 to December 2024. Each state’s housing prices are provided as columns for every month, resulting in a wide-format dataset. Key columns include:

- **RegionID**: Unique identifier for each state.
- **RegionName**: State names.
- **Monthly Prices**: Columns named in the format `YYYY-MM-DD`, representing housing prices for a given month.

---

## Data Preparation

### Initial Dataset Challenges

1. **Wide Format**: The dataset contained over 300 columns, making it difficult to analyze trends directly.
2. **Null Values**: Several columns contained missing values, which needed to be addressed to ensure accuracy.
3. **Date Format in Columns**: Monthly data columns required processing for aggregation and filtering.
4. **Affordability Ranking**: The dataset included a "Rank" column, which needed clarification and utilization.

### Data Cleaning Process

1. **Handling Missing Values**:
   - Null values in the price columns were replaced with the column-specific averages using Power Query.
2. **Column Removal**:
   - Irrelevant columns such as `Column4` and `Column5` were removed which included the keyword "state" as a single entry and blank entries respectively.
3. **Aggregation**:
   - Monthly columns were used directly without unpivoting to preserve the pivoted format.
4. **Affordability Ranking**:
   - The "Rank" column was interpreted as affordability ranking, indicating relative housing affordability.
5. **Validation**:
   - All transformations were validated to ensure accuracy, and duplicate rows or inconsistencies were addressed.

---

## Dashboard Features

### Key Metrics

1. **Highest Average Price**:
   - Identifies the state with the highest average housing price across all years.
2. **Average Price (2024)**:
   - Highlights the average 3-bedroom housing price for the most recent year.
3. **Highest Growth**:
   - Calculates the state with the steepest price growth from 2000 to 2024.

### Visuals and Insights

1. **Trend of Housing Prices Over Time**:

   - **Question**: How have housing prices changed over time from the pandemic period and what are the top 5 states with the highest growth?
   - **Visual Type**: Line Chart
   - **Insight**: Tracks price trends for states such as Hawaii, California, and Washington to identify growth patterns.

2. **State-Wise Average Housing Price**:

   - **Question**: What are the states with highest average housing price ?
   - **Visual Type**: Bar Chart
   - **Insight**: Highlights top 10 states .

3. **Housing Price Distribution**:

   - **Question**: What is the distribution of housing prices for all states in 2024?
   - **Visual Type**: column chart
   - **Insight**: Demonstrates the spread of housing prices using range to group price ranges.

4. **Top 10 Affordable States**:

   - **Question**: Which states are the most affordable?
   - **Visual Type**: Horizontal Bar Chart
   - **Insight**: Displays states like Wyoming and Vermont as the most affordable options.

5. **Top 5 Contributing States in Real Estate (2024)**:

   - **Question**: Which states contribute the most to the housing market in 2024?
   - **Visual Type**: Pie Chart
   - **Insight**: Shows Hawaii and California as major contributors.

---

## Technical Implementation

### Excel Techniques

1. **Power Query**:
   - Used for data cleaning, replacing nulls, and aggregating data.
2. **Pivot Tables**:
   - Created for calculating metrics like average prices and top contributors.

---

## Insights Derived

1. **Hawaii Dominates in Price Growth**:
   - Hawaii shows the steepest price growth from 2000 to 2024, indicating significant economic development.
2. **Wyoming is the Most Affordable**:
   - Consistently ranks as the most affordable state.
3. **Price Distribution Shows Concentration**:
   - Most housing prices in 2024 fall between \$600,000 and \$900,000.

---

## Future Improvements

1. **Dynamic Interactivity**:
   - Introduce VBA-based buttons for additional functionality.
2. **Integration with Power BI**:
   - Extend the project by creating a Power BI version for advanced analytics.
3. **Updated Dataset**:
   - Incorporate newer data to keep the dashboard relevant.

---

This project not only showcases advanced Excel skills but also demonstrates the ability to transform raw data into meaningful insights. Perfect for showcasing your data analysis expertise in portfolio submissions!



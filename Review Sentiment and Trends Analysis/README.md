# Review Sentiment and Trend Analysis Dashboard

## Introduction

The **Review Sentiment and Trend Analysis Dashboard** is an advanced analytical tool designed to provide key insights from customer review data. This dashboard helps businesses understand trends in review sentiments, product popularity, and the effectiveness of reviews marked as helpful. By leveraging detailed data transformation, calculated columns, and measures, the project creates an intuitive interface to explore key business questions.

---

## Table of Contents

1. [Dataset Information](#dataset-information)
2. [Project Objectives](#project-objectives)
3. [Dashboard Features](#dashboard-features)
4. [Key Calculated Columns and Measures](#key-calculated-columns-and-measures)
5. [Detailed Chart Descriptions and Insights](#detailed-chart-descriptions-and-insights)
6. [Conclusion](#conclusion)

---

## Dataset Information

The dataset used for this project includes detailed customer review data, which contains the following key columns:

- **Id:** Unique identifier for each review.
- **ProductId:** Unique identifier for each product.
- **UserId:** Identifier for the reviewer.
- **Score:** Rating provided by the reviewer (scale: 1 to 5).
- **HelpfulnessNumerator:** Number of users who found the review helpful.
- **HelpfulnessDenominator:** Total number of users who voted on the review.
- **Summary:** Short description or summary of the review.

---

## Project Objectives

The main goals of the project are:

1. To analyze customer reviews and uncover trends in product popularity and sentiment.
2. To evaluate the relationship between review helpfulness and product ratings.
3. To provide an intuitive, interactive dashboard for exploring data insights.

---

## Dashboard Preview

Below is a snapshot of the interactive dashboard: ![Banking Churn Dashboard](https://github.com/CodeVistaPro/Excel-Projects/blob/main/Review%20Sentiment%20and%20Trends%20Analysis/Screenshot%202025-01-27%20154503.png)

---

## Dashboard Features

The dashboard is designed to present insights clearly and interactively. It includes:

### Key Performance Indicators (KPIs):

- **Total Reviews:** Total number of reviews in the dataset.
- **Average Review Score:** The mean score across all reviews.
- **Popular Product:** The product category with the most reviews.
- **Most Reviewed Year:** The year with the highest number of reviews.

### Charts:

1. **Popular Product (Bar Chart):** Highlights review counts across product categories.
2. **Frequent Months (Line Chart):** Identifies months with peak review activity.
3. **Review Trends (Line Chart):** Tracks the number of reviews over the years.
4. **Review Distribution (Pie Chart):** Displays the breakdown of scores.
5. **Helpfulness Level (Bar Chart):** Shows the proportion of reviews based on their helpfulness levels.

### Filters:

- **Score Filter:** Filter data by review scores.
- **Year Filter:** Focus on specific years of review activity.
- **Products Filter:** Explore specific product categories.

---

## Key Calculated Columns and Measures

1. **Helpfulness Ratio:** A measure of how helpful a review is.

   - Formula: `= HelpfulnessNumerator / HelpfulnessDenominator`

2. **Rounded Helpfulness Ratio:** Cleaner values for better visualization.

   - Formula: Rounded to one decimal place in Power Query.

3. **Total Reviews (KPI):** Count of all unique reviews.

   - Formula: `= COUNTA(Reviews[Id])`

4. **Popular Product:** Derived from a pivot table counting reviews by product category.

5. **Most Reviewed Year:** Determined from a pivot table sorted by review counts.

---

## Detailed Chart Descriptions and Insights

### 1. Popular Product (Bar Chart):

- **Purpose:** Identify which product categories receive the most reviews.
- **Key Insight:** The "Food" category has the highest review count, indicating strong customer engagement.

### 2. Frequent Months (Line Chart):

- **Purpose:** Highlight months with peak review activity.
- **Key Insight:** October shows a significant spike in reviews, possibly linked to seasonal trends.

### 3. Review Trends (Line Chart):

- **Purpose:** Show yearly growth in review counts.
- **Key Insight:** Reviews have steadily increased, reflecting growing customer interaction.

### 4. Review Distribution (Pie Chart):

- **Purpose:** Summarize the proportion of different scores.
- **Key Insight:** Over 60% of reviews have a score of 5, indicating high customer satisfaction.

### 5. Helpfulness Level (Bar Chart):

- **Purpose:** Examine the helpfulness of reviews.
- **Key Insight:** The majority of reviews are marked as "Helpful," emphasizing customer reliance on peer feedback.

---

## Conclusion

The **Review Sentiment and Trend Analysis Dashboard** is a comprehensive tool for analyzing customer reviews and deriving actionable insights. With its interactive features, it empowers businesses to understand trends, improve product offerings, and enhance customer satisfaction.

Feel free to explore the dashboard and leverage the insights to drive your business decisions!


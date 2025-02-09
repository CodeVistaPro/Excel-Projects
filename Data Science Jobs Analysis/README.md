# Data Science Jobs Analysis Dashboard - 2024

## 📚 Introduction

Welcome to the **Data Science Jobs Analysis Dashboard** repository! This project showcases a comprehensive analysis of the job market in the field of data science for the year 2024. With an emphasis on salaries, industries, hiring trends, and skill requirements, this interactive dashboard provides valuable insights for aspiring data professionals and hiring managers alike.

## Dashboard Preview

Below is a snapshot of the interactive dashboard: ![Banking Churn Dashboard](https://github.com/CodeVistaPro/Excel-Projects/blob/main/Data%20Science%20Jobs%20Analysis/Screenshot%202025-01-26%20152811.png)

---

## 📖 Table of Contents

- [Introduction](#-introduction)

- [Features](#-features)

- [Project Workflow](#-project-workflow)

- [Dashboard Overview](#-dashboard-overview)

  - [Key Insights](#key-insights)
  - [Visualizations](#visualizations)

- [Technologies Used](#-technologies-used)

## ✨ Features

- **KPI Cards**: Highlight key metrics like average salary, total jobs, and most in-demand skills.
- **Top 10 Analysis**: Visualizations for top states, industries, and companies based on salaries and hiring trends.
- **Interactive Slicers**: Filter data by state or job title to tailor the analysis.
- **Skill Insights**: Understand the most in-demand technical skills like Python, Excel, AWS, etc.
- **Distribution Analysis**: Analyze salary and rating distributions to identify trends and outliers.

## 🔄 Project Workflow

1. **Data Cleaning**:
   - Removed unnecessary words from job titles for better visualization.
   - Standardized columns like salaries and converted values into consistent formats (e.g., `$53K`).
   - Filtered invalid age values (e.g., ages > 70 or < 20 were set to NULL).
2. **Data Transformation**:
   - Created new columns, such as `Salary Range`, `Age Range`, and cleaned salary columns.
   - Grouped ratings into bins (e.g., 1-2, 2-3, etc.) for better distribution analysis.
3. **Dashboard Creation**:
   - Designed and built an interactive dashboard in Excel using Pivot Tables, slicers, and charts.

## 🟠️ Dashboard Overview

### Key Insights

- **Average Salary**: \$100,626 across data science roles.
- **Top Hiring Companies**: Reynolds American, Takeda, MassMutual, etc.
- **In-Demand Skills**: Python is the most sought-after skill, followed by Excel, AWS, and Spark.
- **Rating Distribution**: Majority of company ratings fall between 3-4, indicating good employer quality.

### Visualizations

1. **KPI Cards**:

   - **Average Salary**: \$100,626
   - **Total Jobs**: 742
   - **Python Req.**: 392
   - **Top Job Title**: Data Scientist (438 postings)

2. **Top 10 States Avg Salary**:

   - **Chart**: Bar Chart
   - **Insight**: California, Illinois, and Washington, D.C., lead in average salaries.

3. **Top 10 Industries**:

   - **Chart**: Vertical Bar Chart
   - **Insight**: Biotech & Pharmaceuticals dominates the industry, followed by Insurance Carriers.

4. **Top Hiring Companies**:

   - **Chart**: Horizontal Bar Chart
   - **Insight**: Reynolds American, Takeda, MassMutual, are among the top recruiters.

5. **Rating Distribution**:

   - **Chart**: Pie Chart
   - **Insight**: 65% of ratings fall between 3-4, showing favorable employer reviews.

6. **Age Range**:

   - **Chart**: Bar Chart
   - **Insight**: Most employees fall in the 30-40 age group.

7. **In-Demand Skills**:

   - **Chart**: Pie Chart
   - **Insight**: Python and Excel are the top skills required.

## 💻 Technologies Used

- **Excel 2019**:
  - Pivot Tables
  - Conditional Columns
  - Interactive Charts
- **Power Query**: For data cleaning and transformation.
- **Formulas**: Used `COUNTIFS`, `SUMIFS`, and `FLOOR` for data aggregation and calculations.

---

Feel free to reach out with feedback or suggestions to improve this project! 🚀



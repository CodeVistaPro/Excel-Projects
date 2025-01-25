# Netflix Movies & Shows Analysis Dashboard

Welcome to the **Netflix Movies & Shows Analysis Dashboard** repository! This project provides an interactive and visually appealing Excel-based dashboard that highlights key insights and trends from Netflix's extensive catalog of movies and TV shows. 🚀

---

## 📜 Introduction

Netflix is one of the largest streaming platforms in the world, with a diverse catalog of movies and TV shows catering to audiences worldwide. This dashboard is designed to help users explore:

- The distribution of genres.
- Trends in content over time.
- The most prominent countries contributing to Netflix's catalog.
- Viewer-favorite genres and ratings.

Whether you're a data enthusiast, Netflix fan, or a business analyst, this dashboard showcases the power of Excel in visualizing large datasets. 🎉

---

## 📚 Table of Contents

1. [Features](#features)
2. [Dataset Details](#dataset-details)
3. [Dashboard Overview](#dashboard-overview)
4. [Technical Details](#technical-details)
5. [Insights](#insights)

---

## ✨ Features

- **Total Titles**: Displays the total number of movies and TV shows in the dataset.
- **Genre Analysis**: Highlights the most popular genres, such as Dramas, Comedies, and Documentaries.
- **Country Contributions**: Identifies top countries contributing to Netflix’s catalog.
- **Growth Over Time**: Visualizes the addition of titles over the years.
- **Content Duration Analysis**: Categorizes movies by duration and TV shows by the number of seasons.
- **Rating Distribution**: Examines the most common content ratings (e.g., TV-MA, PG-13).
- **Interactive Slicers**: Allows filtering by country, year added, and content type.

---

## 📊 Dataset Details

- **Source**: Netflix Titles dataset
- **Columns**:
  - `type`: Indicates whether the title is a "Movie" or "TV Show".
  - `title`: Name of the title.
  - `director`: Name(s) of the director(s).
  - `cast`: Main cast members.
  - `country`: Country of origin.
  - `date_added`: Date the title was added to Netflix.
  - `release_year`: Year the title was released.
  - `rating`: Content rating (e.g., PG, TV-MA).
  - `duration`: Duration in minutes (for movies) or seasons (for TV shows).
  - `listed_in`: Genres/categories the title belongs to.

---

## 🖥️ Dashboard Overview

The dashboard consists of the following sections:

### **1. Summary Cards** 📋

- **Total Titles**: 8808
- **Number of Movies**: 6131
- **Number of TV Shows**: 2676
- **Top Country**: United States
- **Common Rating**: TV-MA

### **2. Visuals** 📈

- **Most-Watched Genres**: A bar chart showcasing popular genres.
- **Top 10 Countries**: Bar chart ranking the countries contributing the most titles.
- **Growth Over Time**: Line chart tracking the yearly addition of titles.
- **Content by Rating**: Bar chart showing the distribution of content ratings.
- **Season Category**: Pie chart categorizing TV shows by the number of seasons.
- **Movie Category**: Pie chart categorizing movies by duration.

### **3. Interactive Slicers** 🎛️

- **Country**
- **Year Added**
- **Type (Movies/TV Shows)**

---

## ⚙️ Technical Details

- **Data Cleaning**:
  - Handled missing values in `duration` and `country` columns.
  - Extracted movie durations and categorized them into "Short", "Medium", and "Long".
  - Categorized TV shows into "Short-Seasoned", "Medium-Seasoned", and "Long-Seasoned".
- **Tools Used**:
  - Excel Power Query for data cleaning and transformation.
  - Pivot Tables and Pivot Charts for visualizations.
  - Conditional formatting for aesthetic improvements.

---

## 💡 Insights

1. **Dramas Lead the Way**:

   - Dramas are the most popular genre, followed by Comedies and Documentaries.

2. **The United States Dominates**:

   - The United States is the top contributor to Netflix's catalog, with over 3210 titles.

3. **Recent Growth**:

   - Significant growth in titles was observed from 2015 onward, reflecting Netflix's global expansion.

4. **Content Ratings**:

   - TV-MA is the most common rating, followed by TV-PG and PG-13.

5. **Duration and Seasons**:

   - Most movies fall in the "Medium" duration category, while TV shows are predominantly "Short-Seasoned".

---

Thank you for exploring the **Netflix Movies & Shows Analysis Dashboard**! 📽️📊 Feel free to reach out with any questions or suggestions. 😊



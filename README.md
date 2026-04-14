# Netflix Dashboard (Power BI)

## Project Overview

This project is an interactive data visualization dashboard built using Power BI to analyze the Netflix Titles dataset. It provides meaningful insights into movies and TV shows available on Netflix across different years, countries, genres, and ratings.

The goal of this project is to understand content trends, identify popular genres, and analyze the growth of Netflix content over time.

---

## Objectives

* Analyze the distribution of Movies and TV Shows
* Identify top genres and most frequent content types
* Study year-wise growth of Netflix content
* Analyze ratings and content classification
* Understand country-wise contribution of content

---

## Dashboard Features

* Total Movies and TV Shows count
* Genre-wise distribution (Top Genres)
* Ratings analysis over time
* Year-wise content growth trend
* Country-wise content distribution
* Movies vs TV Shows comparison

---

## Analysis Performed

* Static Analysis: Based on historical Netflix dataset
* Trend analysis to identify growth patterns
* Comparative analysis between Movies and TV Shows
* Identification of most popular genres and countries
* Visualization of ratings distribution

---

## Dataset Information

* Dataset: Netflix Titles Dataset
* Attributes include:

  * Title
  * Genre
  * Country
  * Release Year
  * Rating
  * Duration
  * Cast & Director

---

## Tools & Technologies Used

* Power BI (Data Visualization & Dashboarding)
* Data Modeling (Star Schema using Dimension Tables)
* Data Cleaning & Transformation

---

## Data Model

The project follows a Star Schema:

* Fact Table: `netflix_titles`
* Dimension Tables:

  * `Dim_Type`
  * `Dim_Country`
  * `Dim_Genre`
  * `Dim_Rating`
  * `DateTable`

This improves performance and enables efficient analysis.

---

## How to Use

1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Explore the interactive visuals and filters

---

## Key Insights

* Movies dominate the platform compared to TV Shows
* Certain genres like Drama and International content are most popular
* Significant growth in content after 2015
* Some countries contribute more content than others

---

## Conclusion

This dashboard helps in understanding Netflix content trends and provides valuable insights using data visualization. It demonstrates how Power BI can be used effectively for business intelligence and decision-making.

---

## Author

Tanisha Arora

---

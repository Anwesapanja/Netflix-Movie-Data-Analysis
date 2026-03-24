# Netflix Movie Data Analysis Dashboard

An interactive Netflix-style content analysis dashboard built using Microsoft Excel / Google Sheets, featuring pivot-based insights and investment vs return analysis.

## Project Title

Netflix Movie Data Analysis Using Google Sheets

## Project Overview

This project analyzes a Netflix-style content dataset to uncover insights related to content distribution, financial performance, and audience indicators.

## The workflow includes:

Data collection from raw dataset
Data cleaning and transformation
Pivot table analysis
Dashboard visualization

The final output is a business-ready dashboard that supports decision-making and exploratory analysis.

## Key Objectives
Analyze content distribution across different types
Compare production budget vs box office revenue
Evaluate average duration and IMDb ratings
Perform country-wise analysis of investment and returns
Build an interactive dashboard for insights

## Project Structure

| Folder                        | File                             | Description                          |
| ----------------------------- | -------------------------------- | ------------------------------------ |
| Raw Dataset                   | Movies.csv                       | Original source dataset              |
| Clean Dataset                 | Clean movies.xlsx                | Cleaned dataset with transformations |
| Clean Dataset                 | Clean movies - movies.pdf        | PDF export of cleaned data           |
| Pivot Tables and Calculations | Movies Pivot Data Analysis1.xlsx | Pivot analysis workbook (v1)         |
| Pivot Tables and Calculations | Movies Pivot Data Analysis2.xlsx | Pivot analysis workbook (v2)         |
| Dashboard                     | Screenshot 2026-02-24 011043.png | Dashboard preview image              |
| Root                          | README.md                        | Project documentation                |

## Data Dictionary

| Column Name         | Data Type | Description                                |
| ------------------- | --------- | ------------------------------------------ |
| movie_id            | Text      | Unique identifier in movie_#### format     |
| title               | Text      | Name of the movie/content                  |
| content_type        | Text      | Type (Movie, TV Series, Documentary, etc.) |
| genre_primary       | Text      | Primary genre                              |
| genre_secondary     | Text      | Secondary genre                            |
| release_year        | Integer   | Year of release                            |
| duration_minutes    | Integer   | Duration in minutes                        |
| rating              | Text      | Content certification rating               |
| language            | Text      | Primary language                           |
| country_of_origin   | Text      | Country of production                      |
| imdb_rating         | Decimal   | IMDb rating (0–10 scale)                   |
| production_budget   | Decimal   | Budget used for production                 |
| box_office_revenue  | Decimal   | Revenue generated                          |
| number_of_seasons   | Integer   | Number of seasons (for series)             |
| number_of_episodes  | Integer   | Number of episodes (for series)            |
| is_netflix_original | Boolean   | TRUE/FALSE indicator                       |
| added_to_platform   | Date      | Date added to platform                     |
| content_warning     | Boolean   | Indicates content warning                  |

## Data Summary
Total Records: 1,040
Total Columns: 18
Missing Values: 0
## Time Range
Release Year: 1953 – 2024
Added to Platform: 2020 – 2025
## Ratings Overview
Min: 0.5
Max: 10.0
Avg: 6.27
## Content Insights
Netflix Originals: 318 (30.58%)
Content Warning: 201 (19.33%)
## Financial Overview
Total Budget: 11.56 Billion
Total Revenue: 67.19 Billion
ROI Ratio: 5.81x
## Content Distribution
Movies: 458 (44.04%)
TV Series: 267 (25.67%)
Documentaries: 142 (13.65%)
Stand-up Comedy: 119 (11.44%)
Limited Series: 54 (5.19%)
## Top Languages
English (608)
Spanish (103)
French (67)
Hindi (60)
Japanese (55)
## Top Countries
USA (543)
South Korea (118)
Canada (102)
UK (88)
Japan (57)
## Data Cleaning Notes
movie_id split into movie + id columns
title removed in cleaned dataset
Dates stored in Excel serial format
## Data Quality Checks
Duplicate IDs: 40
Duplicate Titles: 262
Series-related fields are mostly zero for non-series records
## Analytics & Dashboard
Pivot Analysis Includes:
Content type-wise analysis
Country-wise financial analysis
Metrics Used:
Content count
Average duration
Average IMDb rating
Total budget & revenue
Seasons & episodes

## 🖼️ Dashboard Preview

![Dashboard](./DashBoard/Screenshot%202026-03-23%20023541.png)

## Tools Used

Microsoft Excel
Google Sheets
Pivot Tables
Pivot Charts
Dashboard Design (KPI Cards)

## Conclusion

This project demonstrates a complete data analytics workflow from raw dataset to dashboard visualization.

## Key Insights:
Movies contribute the highest share and revenue
Strong ROI (~5.8x) across the dataset
USA dominates in investment and returns
Content type comparison helps identify performance patterns

## Future Enhancements
Add time-based trend analysis
Compare Netflix Originals vs Non-Originals
Create a separate data dictionary file
Implement data validation and duplicate checks
content_warning	Boolean	Content warning


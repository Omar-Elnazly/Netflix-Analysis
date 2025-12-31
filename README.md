# 📺 Netflix Movies and TV Shows Analysis

An exploratory data analysis (EDA) project on Netflix's content library using Python and data visualization tools to uncover trends in movies and TV shows available as of 2021.


## Overview

This project explores the Netflix dataset to analyze:

-  Distribution of Movies vs. TV Shows
-  Popular genres and how they changed over time
-  Content ratings and trends
-  Duration analysis and outlier detection
-  Country-wise production
-  Frequently appearing actors

The goal is to extract actionable insights and visualize content patterns on Netflix.


## Dataset
⚠️ Note: The dataset is not included in this repository due to size/licensing reasons.
- Source: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Rows: 8,807
- Columns: 12 (title, cast, director, release year, rating, genre, country, etc.)


## Tools & Libraries

- Python 3
- pandas
- matplotlib
- seaborn


## Key Analyses

- **Data Cleaning**: Removed nulls and standardized duration
- **Duration Trends**: Average movie durations over the years
- **Genre Popularity**: Top 5 genres across time using line plots
- **Ratings Distribution**: Pie chart and stacked bar analysis from 2000–2021
- **Movies vs. TV Shows**: Comparisons by type, genre, country, and actors
- **Outlier Detection**: Long (>210 mins) and short (<30 mins) movie highlights


## Key Insights

- **Movies dominate** the platform, but **TV shows are steadily increasing**.
- Most popular **movie genres**: Drama, Comedy, Documentary  
- Most popular **TV show genres**: International, Drama, Reality
- **Top countries**: USA, India, UK, Japan
- **Ratings**: Movies are mostly TV-MA and R-rated; TV shows are more family-friendly
- **Actors**: Several actors have frequent appearances across formats

## ⭐️ Give a Star!

If you found this project helpful or interesting, feel free to ⭐️ star this repository — it helps others discover it too!



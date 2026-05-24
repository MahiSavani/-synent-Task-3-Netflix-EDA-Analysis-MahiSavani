# 🎬 Netflix EDA — Exploratory Data Analysis

A data analysis project exploring trends, content distribution, and patterns in the Netflix titles dataset using Python.


## 📌 Overview

This notebook performs a structured exploratory data analysis (EDA) on the Netflix dataset to uncover insights about content types, genres, ratings, release trends, and country-wise production.


## 📂 Dataset

- **Source:** `netflix_titles.csv`
- **Features:** Title, Type (Movie/TV Show), Country, Release Year, Rating, Genre, etc.


## 🔍 Analysis Performed

| Section | Description |
|---|---|
| Summary Statistics | Shape, data types, null values, descriptive stats |
| Correlation Analysis | Heatmap of numerical variable correlations |
| Movies vs TV Shows | Distribution of content types |
| Content Added Per Year | Year-wise content growth trend |
| Ratings Distribution | Most common content ratings |
| Top 10 Countries | Countries producing the most Netflix content |
| Release Year Distribution | Histogram with KDE of release years |
| Top Genres | Most popular genres on the platform |


## 💡 Key Insights

- Netflix has **more Movies than TV Shows** in its library.
- Content additions **grew rapidly after 2015**, peaking between 2017–2020.
- The **United States, India, and the United Kingdom** are the top content-producing countries.
- **TV-MA and TV-14** are the most frequent content ratings, indicating a focus on teen and adult audiences.
- **Drama, International Movies, and Comedy** are the dominant genres.
- Most content was released **after the year 2000**, reflecting Netflix's focus on modern entertainment.


## ✅ Conclusion

This EDA reveals that Netflix has strategically expanded its content library with a strong emphasis on Movies, mature-rated content, and international productions. The rapid growth post-2015 highlights Netflix's aggressive global expansion strategy. With Drama, Comedy, and International Movies dominating the platform, Netflix clearly caters to a diverse, worldwide audience. The dataset is largely categorical, limiting deep statistical correlation, but the visual analysis provides clear and actionable trends.


## 🛠️ Tech Stack

- **Python 3**
- `pandas` — data manipulation
- `numpy` — numerical operations
- `matplotlib` — visualizations
- `seaborn` — statistical plots
- **Google Colab** — development environment

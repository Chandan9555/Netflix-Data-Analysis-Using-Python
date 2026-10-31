# 🎬 Netflix Data Analysis Using Python

## 📌 Short Description / Purpose

This project focuses on Exploratory Data Analysis (EDA) of Netflix Movies and TV Shows using Python. The main objective is to explore Netflix's content library, understand content distribution, analyze movie durations, identify top content-producing countries, and study release trends over the years.

The project uses data cleaning, data manipulation, and data visualization techniques to extract meaningful insights from the Netflix dataset.

## 🛠️ Tech Stack

- **Python** – Programming language
- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Data visualization
- **VS Code** – Development environment

## 📂 Data Source

- Dataset: Netflix Movies and TV Shows
- File Name: `netflix_titles.csv`
- Original Records: 8,807
- Total Columns: 12

The dataset contains information about:
- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In (Genre)
- Description

## ✨ Features / Highlights

### 1. Data Cleaning
- Loaded the Netflix dataset using Pandas.
- Removed records containing missing values in Type, Release Year, Rating, Country, and Duration.
- Retained 7,970 records for analysis.

### 2. Movies vs TV Shows Analysis
- Compared the total number of Movies and TV Shows.
- Created a bar chart to visualize content distribution.

### 3. Content Rating Analysis
- Analyzed the distribution of Netflix content ratings.
- Created a pie chart to display the percentage of different ratings.

### 4. Movie Duration Analysis
- Extracted movie duration in minutes.
- Converted duration values into integer format.
- Created a histogram to understand the distribution of movie durations.

### 5. Release Year Analysis
- Analyzed the number of Netflix titles released in different years.
- Created a scatter plot to visualize release-year trends.

### 6. Top 10 Countries Analysis
- Identified the top 10 countries based on the number of Netflix titles.
- Created a horizontal bar chart for comparison.

### 7. Movies vs TV Shows Release Trends
- Compared yearly Movie and TV Show releases.
- Created two line charts to understand their release patterns over time.

## 📊 Project Visualizations

The project generates the following visualizations:

| Visualization | Description |
|---|---|
| `movies_vs_tvshows.png` | Movies vs TV Shows comparison |
| `Content_Rating_pie.png` | Percentage of content ratings |
| `movie_duration_histogram.png` | Distribution of movie durations |
| `release_year_Scatter.png` | Release year vs number of shows |
| `top10_countries.png` | Top 10 countries by number of shows |
| `movies_tv_shows_comparison.png` | Yearly release comparison |

## 💡 Key Insights

- Movies represent a larger portion of the Netflix content library than TV Shows.
- TV-MA is the most common content rating in the analyzed dataset.
- Most movies have durations concentrated around 80–120 minutes.
- Netflix content releases increased significantly in recent years.
- The United States contributes the highest number of titles, followed by India.
- Movie releases are higher than TV Show releases across most years.

## 🎯 Learning Outcomes

- Learned practical data cleaning using Pandas.
- Improved Python data manipulation skills.
- Understood Exploratory Data Analysis (EDA).
- Practiced different types of data visualizations.
- Learned how to identify patterns and trends from real-world datasets.
- Improved analytical and problem-solving skills.

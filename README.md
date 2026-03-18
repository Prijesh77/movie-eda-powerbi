🎬 Movie Blockbuster Analysis

Exploratory Data Analysis on TMDB Movies Dataset
Overview

An end-to-end data analysis project exploring what makes a movie a blockbuster.
This project covers data cleaning, exploratory analysis, and interactive visualization
using Python and Power BI on a dataset of 5,000+ movies from TMDB.

Key Questions Answered

Which genres earn the most revenue?

Does a bigger budget guarantee box office success?

What is the best month to release a movie?

Do longer movies get higher audience ratings?

Which movies are the most profitable of all time?

Dataset
TMDB 5000 Movies Dataset — Download from Kaggle

Download tmdb_5000_movies.csv and place it in the data/ folder before running the notebook.
Python Analysis — Key Steps

1. Data Cleaning

Removed movies with missing budget or revenue (zero values)

Parsed the JSON-encoded genres column to extract primary genre

Extracted release month and year from date column

Created new columns: Profit and ROI

2. Exploratory Analysis

Distribution of revenue, ratings, and runtime

Average revenue by genre (top 12)

Budget vs revenue scatter plot with trend line

Revenue trend by release month

Rating vs runtime bucket comparison

Top 10 most profitable movies table

Correlation heatmap of all numeric variables

Power BI Dashboard — Features

4 KPI cards: Total Revenue, Avg Rating, Avg ROI, Movies Analysed

Bar chart: Average revenue by genre

Donut chart: Genre distribution

Scatter chart: Budget vs revenue

Table: Top 10 most profitable films

Year and genre slicers for cross-filtering all visuals


Key Findings

1 Animation and Adventure genres earn the highest average revenue

2 Budget and revenue have a strong correlation of ~0.73

3 May, June, July and December are peak revenue months

4 Movies in the 120–150 min range earn the highest audience ratings

5 A small percentage of films generate most of the industry's total profit

How to Run

bash# 1. Clone the repository

git clone https://github.com/yourusername/movie-eda-powerbi.git

cd movie-eda-powerbi

 2. Install dependencies

pip install -r requirements.txt

# 3. Launch the notebook

jupyter notebook notebooks/movie_eda.ipynb

For the Power BI dashboard, open dashboard/movie_dashboard.pbix in Power BI Desktop.

Author

Prijesh Shrestha

www.linkedin.com/in/prijeshsth77





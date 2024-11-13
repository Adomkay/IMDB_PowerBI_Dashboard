# IMDB Movie Data PowerBI_Dashboard

This Power BI dashboard provides detailed insights into movie sales, ratings, and genres. It includes various visuals that showcase trends and correlations, as well as high-level summary cards that give an overview of key metrics. Below is an explanation of each visual and the findings derived from them.

# Summary Cards
## 1. Total Sales
Description: Displays the total sales across all movies in the dataset.
Insight: This card provides a high-level view of the overall box office sales performance.

## 2. Average IMDB Rating
Description: Displays the average IMDB rating across all movies.
Insight: This value represents the general quality rating of movies in the dataset, giving a sense of how well they were received by audiences.

## 3. Average Sales Per Movie
Description: Displays the average sales per movie across all titles.
Insight: This gives an idea of how each movie, on average, performed in terms of sales.

# Visuals
## 1. Line Chart: Average IMDB Rating by Sales Category
Description: A line chart showing the relationship between IMDB ratings and movie sales categories.
Insight: This chart demonstrates a positive correlation between higher IMDB ratings and higher movie sales. As the IMDB rating increases, movies tend to generate higher sales. This suggests that well-rated movies tend to be more commercially successful.

## 2. Stacked Column Chart: Weighted Sales by Season and Genre
Description: A stacked column chart that shows the weighted sales of movies broken down by season (Spring, Summer, Fall, Winter) and genre.
Insight: The chart clearly highlights the seasonality effects on movie performance:
Action and Adventure movies perform best in Spring and Summer, likely due to blockbuster releases targeting larger audiences during these months.
Drama movies perform better during Fall and Winter, which may align with award season releases or more family-oriented films released around the holiday season.

## 3. Heatmap: Weighted Sales by Year, Genre, and Age Rating
Description: A heatmap displaying the weighted sales of movies from 2000 to 2017, broken down by genre and age rating (PG, PG-13, R, etc.).

# Insight:
## Genre Popularity: 
Adventure movies consistently perform the best across all years, followed by Action, Comedy, and Drama genres. This indicates that action-packed, adventurous movies tend to dominate the box office year after year.
## Age Rating Popularity:
For Action and Adventure genres, PG and PG-13 rated movies tend to perform the best.
For Comedy films, PG, PG-13, and R rated movies have been the best performers.
Drama movies perform best with PG-13 and R ratings. This may suggest that mature, more nuanced stories in drama tend to attract larger audiences.

# Explanation of Weighted Sales
In this analysis, weighted sales have been used to fairly distribute total sales across genres when a movie is mapped to multiple genres.

# Why is this necessary? 
Many movies belong to more than one genre (e.g., a movie could be both a "Comedy" and "Action" movie). If we attributed all the sales of the movie equally to each genre, it could lead to overrepresentation of certain genres.

# How is it calculated?

For each movie, the total sales are divided by the number of genres the movie belongs to.
For example, if a movie has $100 million in total sales and belongs to 3 genres, the weighted sales for each genre would be $33.33 million. This ensures that the sales are attributed proportionally across the genres.
By using weighted sales, we can get a more accurate representation of how each genre contributes to the overall box office performance, even when movies span multiple genres.

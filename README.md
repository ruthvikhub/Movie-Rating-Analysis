# Movie-Rating-Analysis
#### Abstract:
Movie rating analysis provides insights into user preferences, genre popularity, and overall movie performance on streaming platforms like IMDB, Netflix, or Prime Video. This project aims to analyze movie rating data to extract key insights such as the distribution of ratings, the correlation between movie genres and ratings, and identifying the top-rated movies. Using Pandas and NumPy, the dataset is cleaned and preprocessed, followed by calculating key statistics like the average rating, number of ratings per movie, and genre-wise performance. Visualizations using Matplotlib and Seaborn help identify trends and patterns in user behavior and movie preferences.

The analysis includes:
1. Cleaning and preprocessing the dataset (handling missing values, duplicates, etc.).
2. Calculating metrics such as average rating, rating distribution, and top-rated movies.
3. Analyzing the relationship between genres, release years, and ratings.
4. Visualizing trends to understand how user preferences vary based on different factors.
   ### Key Steps in Code:
1. **Loading and Cleaning Data**: The dataset is loaded into a **Pandas** DataFrame. Missing values in the `Rating` column are filled with `0`, and duplicates are removed. The release date is also converted to a `datetime` format.
2. **Feature Engineering**: Extracts the release year from the release date, and genres are split into multiple rows for better analysis.
3. **Aggregating Metrics**:
   - Average Rating: Calculated for each movie and displayed for the top 10 movies.
   - Number of Ratings: The count of ratings for each movie.
4. **Visualizations**:
   - A **distribution plot** for movie ratings to understand how ratings are spread across the dataset.
   - A **bar plot** for average ratings per genre.
   - A **line plot** showing how average ratings have changed over time by release year.
5. Genre Analysis: The dataset is split by genre, and the top-rated movie is displayed for each genre.
6. Saving the Cleaned Data: The cleaned dataset is saved to a new CSV file for further analysis or machine learning tasks.

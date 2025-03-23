# MovieLens Data Analysis

## Project Overview
This project analyzes the MovieLens dataset to understand movie rating patterns, genre preferences, and user behavior. The goal is to extract valuable insights that can help improve user engagement and overall experience for movie recommendation platforms.

## Dataset Description
The analysis utilizes three primary datasets:
- **movie.csv**: Contains information about movies and their genres
- **user.csv**: Contains demographic information about users who rated movies
- **ratings.csv**: Contains actual ratings given by users to particular movies

## Key Findings

### Movie Genre Analysis
- The dataset spans **18 distinct genres** of films
- **Top 5 genres** by number of movies are Drama, Comedy, Action, Thriller, and Romance
- **50% of movies** are classified under multiple genres
- **Film-Noir** has the highest average rating (3.92), while **Fantasy** has the lowest (3.21)
- **72% of genres** have an average rating above 3.5

### Top-Rated Movies
- Highest-rated movies include "Great Day in Harlem, A", "Prefontaine", and others
- Lowest-rated movies include "Shadow of Angels (Schatten der Engel)", "Power 98", and others
- 334 movies received more than 100 ratings
- "Close Shave, A" achieved the highest average rating among frequently-rated movies (112 ratings)
- "Star Wars" received the most ratings while maintaining an excellent 4.35 average

### User Demographics and Behavior
- **Gender distribution**: 71% male, 29% female users
- Average ratings by gender are nearly identical (approximately 3.53)
- Non-working users tend to give higher ratings than working professionals
- Healthcare workers give the lowest average ratings

## Methods Used
- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Pattern recognition

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Future Work
- Implement recommendation algorithms based on these insights
- Analyze temporal trends in movie ratings
- Explore correlation between movie metadata and ratings
- Analyze user rating patterns over time

## License
This project is licensed under the MIT License - see the LICENSE file for details.

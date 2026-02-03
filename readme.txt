#MovieLens 100K Data Analysis

## Project Overview
This project performs exploratory data analysis on the MovieLens 100K dataset to understand user movie rating behavior, popular movies, and genre-wise rating trends.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
MovieLens 100K dataset containing:
- 100,000 movie ratings
- 1,682 movies
- Genre information for each movie

## Key Analysis Performed
- Data cleaning and preprocessing
- Merging ratings and movie metadata
- Identification of top-rated movies (with minimum rating threshold)
- Analysis of most popular movies
- Genre-wise average rating analysis
- Visualization of genre trends

## Key Insights
- Highly popular movies are not always the highest rated
- Documentary, Film-Noir, and War genres receive higher average ratings
- Drama and Comedy dominate in number of movies but vary in quality
- Combining popularity and rating gives better recommendation signals

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook

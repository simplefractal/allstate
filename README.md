# Day 1

## 1.0 Objectives
Students will

- define their goals for the 5-day workshop
- learn and apply the basics of Python
- learn and apply the basics of Pandas
- get comfortable with the Jupyter Notebook

## 1.1 Agenda
0. Welcome
1. Student Intros
2. Instructor Intro
3. Overview of the Week
4. Why Python? Why Data Science?
5. Intro to Python
6. Pandas Basics

## 1.2 Overview of the Week
- Day 1: Python & Pandas
- Day 2: Pandas, Plotting, and Intro to Data Science
- Day 3: Modeling Part 1
- Day 4: Modeling Part 2 & Intro to Unsupervised Learning
- Day 5: Data Science Infrastructure, EDA, NLP and Capstone Projects

## 1.3 Why Python? Why Data Science?
## 1.4 Philosophy of Practice
## 1.5 The Jupyter Notebook
## 1.6 Numerical Data, Variables & Strings
## 1.7 Booleans
## 1.8 Lists
## 1.9 Dictionaries
## 1.10 If / Else
## 1.11 For Loops
## 1.12 Functions (Part 1)
## 1.13 Functions (Part 2)
## 1.14 List Comprehensions
## 1.15 Using Documentation & The `random` library
## 1.16 Handling CSV data
We'll use [this data](https://s3.amazonaws.com/simple-fractal-workshops/movie_history_for_user.csv) for our exploration into the `csv` library.
## 1.17 Pandas Basics
We'll use [this data](https://s3.amazonaws.com/python-level-2/sales-funnel.csv) for our exploration into `pandas`.
## 1.18 Optional Lab: Basic Movie Recommendations
Suppose we have [this movie data](https://drive.google.com/file/d/0Byveb6yWfKu2ZThzYno2RV9uSHc/view?usp=sharing)

And that we have an objective recommendation scoring function as follows

```
objective_score = 2.3 * imdb_score - (release_year / 2000) + 1.5 (genre_is_either_scifi_or_fantasy)
```

And that we also want to personalize these recommendations for a given user, so on top of the objective score, we want to give a 2.5 bonus for movies released before 1970 if the user prefers old movies and a 3.5 bonus if the movie genre matches one of the movie favorites.

Suppose that the user dictionary is of the following form:

```
{
    “id”: 12,
    “likes_old_movies”:  True,
    “favorite_genres”: “Action|Sci-Fi”
}
```

## Exercises
1. Implement a function called `get_score` that takes a movie’s imdb title id, which you can get from the movie_imdb_link (e.g. in http://www.imdb.com/title/tt2070597/?ref_=fn_tt_tt_1', the title id is “tt2070597”) and returns the fractal score for that movie.
2. Implement a function called `get_user_score` that takes the movie’s imdb title id and a user dictionary (a.k.a. hash) and returns the user-specific score for that movie.
3. Implement a function called `get_top_10_movies_for_user` that takes the user dictionary and returns the names of the top 10 movies and their corresponding user-specific fractal scores.
4. Run `get_top_10_movies_for_user` for the example user dictionary specified in the section titled The Data above.

# Day 2
## 2.0 Objectives
Students will

- use more `pandas` functionality to reshape & transform their data
- practice basic data munging
- apply basic `matplotlib` plotting from within `pandas` dataframes
- learn `seaborn` plotting
- create more novel plots with `plotly` and `cufflinks`

## 2.1 Python Review via an Exercise
## 2.2 Pandas Basic Review
Let's work with this data: https://drive.google.com/file/d/0Byveb6yWfKu2ZThzYno2RV9uSHc/view?usp=sharing
## 2.3 More Boolean Masks
## 2.4 Data Aggregation
Let's go back to our Sales Funnel data set.
## 2.5 Pivot Tables
## 2.6 Cross Tabulation
## 2.7 Groupby
## 2.8 Lambda Functions
## 2.9 Data Transformation & Munging 101
## 2.10 Text Manipulation
## 2.11 Why Data Viz? What's EDA?
## 2.12 Plotting from Pandas DataFrame via `matplotlib`
## 2.13 Intro to `seaborn`
Compute the prices per rep for the other product types: Maintenance, Monitor and Software and save them into following variables, similar to how we got `cpu_prices_pre_rep`:
## 2.14 Plot.ly Heatmap
Let's use this dataset: https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/hotdog-eaters.csv

We can use my API key: api_key = "gRlD3V1yDbklDSCyqlwO"

## 2.15 Geographical plot (a.k.a. Chloropleth)
Let's use this data: https://raw.githubusercontent.com/plotly/datasets/master/2011_us_ag_exports.csv

## 2.16 Optional Time Series Lab (with Cuff Links)
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/aapl.csv
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/goog.csv

## 2.17 Lab: Exploratory Data Analysis (EDA)
Let's explore the agricultural data further.


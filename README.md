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
- learn the basics of linear regression, our first predictive model
- work on an in-class regression modeling lab

## 2.1 Agenda
0. Welcome & Any Questions/Thoughts from Day 1?
1. More `pandas`
2. Data Munging 101
3. Why data viz? What's EDA?
4. Basic plotting with `matplotlib` via `pandas`
5. Intro to `seaborn`
6. Novel plots with `plotly` and `cufflinks`
7. Lab 1: Basic EDA with Data Visualization
7. How Data Science Works at a High-level
8. Intro to Linear Regression
9. Code Example of Linear Regression
10. Lab 2: Linear Regression Applied

## 2.2 More `pandas`
We'll continue using [this dataset](https://s3.amazonaws.com/python-level-2/sales-funnel.csv).

### 2.21 Pivot tables
### 2.22 Cross-tabulation

## 2.3 Data Munging 101
Let's use [this dataset](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/rock.csv).

### 2.31 lambda functions
### 2.32 `value_counts()`
### 2.33 `groupby`

## 2.4 Why data viz? What's EDA?
- [NYC Restaurant Grades](https://fivethirtyeight.com/features/how-data-made-me-a-believer-in-new-york-citys-restaurant-grades/)
- [NY Times Election Map](https://www.nytimes.com/elections/results/president)

## 2.5 Basic plotting via `pandas` and `matplotlib`


## 2.6 Intro to `seaborn`

## Datasets for Exercise
- [AAPL](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/aapl.csv)
- [GOOG](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/goog.csv)

## 2.7 Novel plots with Plot.ly
### Heat Map
- [Hotdog Eaters](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/hotdog-eaters.csv)

### Geographical Plot
- [US Agricultural Exports](https://raw.githubusercontent.com/plotly/datasets/master/2011_us_ag_exports.csv)

## 2.8 Lab 1: EDA & Data Viz

## 2.9 How Data Science Works at a High Level

### For Discussion
Suppose we only have the following data set.

release_year | genre | imdb_score | fb_fan_count | watched
--- | --- | --- | --- | ---
2011 | Sci-Fi | 6.5 | 750000 | 1
1977 | Romance | 8.8 | 1500 | 0
1977 | Sci-Fi  | 7.5 | 8688 | 1
... | ... | ... | ... |...

0. What should be the target?
1. What are the features?
2. What data should we train it on?
3. What data should we test it against?

## 2.10 The Theory of Linear Regression

## 2.11 Code Example of Linear Regression

## 2.12 Lab 2: Linear Regression Applied
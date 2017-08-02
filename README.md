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

# Day 3
## 3.0 Objectives
- learn logistic regression, SVM, kNN
- apply these models to real datasets

## 3.01 Time Series Lab
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/aapl.csv
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/goog.csv

## 3.1 The Mechanics of Data Science
## 3.2 Data Science Terms & Definitions
- supervised learning
- unsupervised learning
- target
- feature
- training set
- validation set
- cross-validation
- model
- regression vs classification

## 3.3 The Theory of Linear Regression
[Gradient Descent Worksheet](https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/Gradient+Descent/GD_worksheet_1.pdf)

## 3.4 Linear Regression Code Sample
This dataset: https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/datasets/Boston_Housing.csv

Description of the data: https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names

## 3.5 Lab: Linear Regression Applied
Let's take a look at [this dataset](https://s3-us-west-2.amazonaws.com/simplefractal-teaching/health_data.csv)

## 3.6 kNN Theory
- Worksheet 1 https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/worksheet_1_kNN.pdf
- Worksheet 2 https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/worksheet_2_kNN.pdf
- Worksheet 3 https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/worksheet_3_kNN.pdf

## 3.7 kNN Applied
Let's use this breast cancer dataset The data: https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/datasets/breast-cancer.csv

### Accuracies plot

## 3.8 Logistic Regression
## 3.9 SVM Theory
The kernel trick: https://www.youtube.com/watch?v=3liCbRZPrZA

### Worksheets
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/SVM/SVM_worksheet_1.pdf
- https://s3-us-west-2.amazonaws.com/ga-dat-2015-suneel/worksheets/SVM/SVM_worksheet_2.pdf

## 3.10 SVM Applied
Let's try it again on the breast cancer data.

### Accuracies plot

### Parametric Grid Search Demo

## 3.11 Lab: Classification Problem
Let's work on this dataset: https://s3-us-west-2.amazonaws.com/simplefractal-teaching/cc_default.csv

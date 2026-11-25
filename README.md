# Zomato Restaurant Data Analysis Using Python

## Project Overview

This project explores Zomato restaurant data using Python. The analysis
focuses on restaurant locations, ratings, online-order availability,
restaurant types, and approximate dining costs for two people.

## Objectives

-   Understand the distribution of restaurants across locations.
-   Explore restaurant ratings.
-   Compare online-order and offline-order restaurants.
-   Identify common restaurant types.
-   Analyze approximate dining costs.
-   Explore relationships between ratings, votes, and cost.

## Tools and Libraries

-   Python
-   Pandas
-   Matplotlib
-   Jupyter Notebook

## Dataset

The notebook reads a CSV file named `zomato.csv`.

The dataset initially contains **51,717 rows and 17 columns**. After
removing duplicate records, dropping selected columns, converting rating
and cost fields to numeric values, and removing rows with missing
ratings or costs, the cleaned dataset contains **41,418 rows and 12
columns**.

> The dataset file is not included in this repository by default. Add
> `zomato.csv` to the repository only if you have permission to share
> it. Otherwise, download or obtain the dataset separately and place it
> in the same folder as the notebook.

## Project Workflow

1.  Import Pandas and Matplotlib.
2.  Load the CSV dataset.
3.  Inspect the data using `head()`, `shape`, `info()`, and
    `describe()`.
4.  Check missing values and duplicate records.
5.  Remove duplicate rows and unnecessary columns.
6.  Clean the rating field by removing `/5` and converting it to
    numeric.
7.  Remove commas from the approximate-cost field and convert it to
    numeric.
8.  Remove rows with missing ratings or approximate costs.
9.  Perform exploratory data analysis and create visualizations.

## Analysis and Visualizations

The notebook includes: - Top 10 locations by restaurant count (bar
chart). - Online-order availability (pie chart). - Distribution of
restaurant ratings (histogram). - Top-rated restaurants (rating-based
table). - Top 10 locations by average rating (bar chart). - Average
ratings for online and offline ordering (bar chart). - Approximate cost
versus restaurant rating (scatter plot). - Top 10 most common restaurant
types (bar chart). - Average approximate cost for two people. -
Correlation analysis of rating, votes, and approximate cost (correlation
heatmap).

## Selected Findings

-   **BTM** has the highest restaurant count in the cleaned dataset
    (3,906).
-   **27,206** restaurants accept online orders and **14,212** do not.
-   The average rating is approximately **3.72** for restaurants
    accepting online orders and **3.66** for those that do not.
-   **Quick Bites** is the most common restaurant type (13,885 records).
-   The average approximate cost for two people is about **603** (in the
    dataset's currency units).
-   The highest average-rated location in the notebook's results is
    **Lavelle Road** (approximately 4.14).

These findings describe the records in this dataset and should not be
treated as current restaurant-market statistics.

## How to Run the Project

1.  Clone or download this repository.

2.  Make sure Python and Jupyter Notebook are installed.

3.  Install the required libraries:

    ``` bash
    pip install pandas matplotlib jupyter
    ```

4.  Place `zomato.csv` in the same folder as the notebook.

5.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

6.  Open `Zomato Restaurant Data Analysis using Python(1).ipynb` and run
    the cells from top to bottom.

## Repository Structure

``` text
Zomato-Restaurant-Data-Analysis/
├── Zomato Restaurant Data Analysis using Python(1).ipynb
├── README.md
└── zomato.csv                 # Include only if you can share the dataset
```

## Skills Demonstrated

-   Data loading and inspection
-   Data cleaning and preprocessing
-   Exploratory Data Analysis (EDA)
-   Grouping and aggregation with Pandas
-   Data visualization with Matplotlib
-   Basic correlation analysis

## Author

Darshan Kavathe

GitHub: [Darshankavathe](https://github.com/Darshankavathe)

# Movie Data Analysis Portfolio Project

This project explores relationships between different features of movies
to understand what factors may influence a film's success. Using Python
for data analysis and visualization, the notebook investigates
correlations between budget, gross revenue, ratings, votes, and other
variables.

The goal of the project is to practice exploratory data analysis (EDA),
data cleaning, and correlation analysis while building clear
visualizations that reveal patterns in movie performance.

------------------------------------------------------------------------

## Project Overview

In this project we analyze a dataset of movies to answer questions such
as:

-   Do higher budgets lead to higher box office revenue?
-   Which movie features are most strongly correlated with financial
    success?
-   Are there hidden relationships between categorical variables such as
    genre, company, or rating?

The analysis focuses on identifying meaningful correlations and
visualizing them using heatmaps and plots.

------------------------------------------------------------------------

## Tools and Libraries

The analysis was performed in **Python** using the following libraries:

-   **Pandas** -- data manipulation and cleaning
-   **NumPy** -- numerical operations
-   **Matplotlib** -- data visualization
-   **Seaborn** -- statistical visualizations and heatmaps

------------------------------------------------------------------------

## Dataset

The dataset contains information about movies including:

-   Movie title
-   Genre
-   Budget
-   Gross revenue
-   Rating
-   Votes
-   Year of release
-   Production company
-   Runtime

These variables allow us to examine both financial and descriptive
aspects of movies.

------------------------------------------------------------------------

## Project Workflow

### 1. Data Import

The dataset is loaded using Pandas and inspected to understand its
structure and columns.

### 2. Data Exploration

Initial exploration includes: - Viewing the dataset - Checking column
data types - Identifying missing values

### 3. Data Cleaning

Missing values are inspected and handled where necessary.\
Categorical variables are converted into numeric representations so they
can be included in correlation analysis.

### 4. Correlation Analysis

Several correlation methods are explored:

-   **Pearson correlation**
-   **Kendall correlation**
-   **Spearman correlation**

Heatmaps are used to visualize relationships between variables.

### 5. Feature Encoding

Categorical features such as genre and company are transformed into
numeric values using factorization so they can be included in the
correlation matrix.

### 6. Identifying Strong Relationships

Correlation pairs are sorted to identify the strongest positive and
negative relationships between movie features.

------------------------------------------------------------------------

## Key Insights

Some of the main observations from the analysis include:

-   **Budget and gross revenue show a strong positive correlation**,
    suggesting higher investment often leads to higher returns.
-   **Votes are also strongly correlated with gross revenue**,
    indicating that more popular movies tend to generate higher box
    office results.
-   Certain categorical features may have weaker correlations but still
    provide useful contextual information.

These findings highlight how financial investment and audience
engagement play an important role in movie success.

------------------------------------------------------------------------

## Visualizations

The project uses several visualizations to explore relationships:

-   Correlation heatmaps
-   Scatter plots
-   Data distribution visuals

These help reveal patterns that are not immediately obvious from the raw
data.

------------------------------------------------------------------------

## How to Run the Project

1.  Clone the repository

git clone https://github.com/`<username>`{=html}/movie-data-analysis.git

2.  Install required libraries

pip install pandas numpy matplotlib seaborn

3.  Open the Jupyter Notebook

jupyter notebook

4.  Run the notebook to reproduce the analysis.

------------------------------------------------------------------------

## Project Structure

movie-data-analysis/ │ ├── Movie Portfolio Project.ipynb ├── README.md
└── dataset.csv

------------------------------------------------------------------------

## Author

**Jessica Dan-Odhomo**

This project was created as part of a data analytics portfolio to
demonstrate skills in:

-   Data cleaning
-   Exploratory data analysis
-   Data visualization
-   Statistical analysis with Python

------------------------------------------------------------------------

## Future Improvements

Possible next steps for this project include:

-   Building predictive models for box office success
-   Expanding the dataset with additional movie metadata
-   Creating interactive dashboards using tools like Plotly or Tableau

------------------------------------------------------------------------

If you have feedback or suggestions, feel free to reach out or open an
issue.

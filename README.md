# 🎬 TMDb Movie Revenue Analysis

This project performs an exploratory data analysis (EDA) on the TMDb movie dataset to understand which factors are associated with higher movie revenue. The analysis uses Python data analysis libraries and focuses on identifying trends, relationships, and patterns without implying causation.

---

## Project Overview

Movies vary widely in terms of budget, genre, audience ratings, and release year. This project explores how these factors relate to movie revenue using real-world data from The Movie Database (TMDb).

The goal is to apply the full data analysis process:
- Data wrangling and cleaning
- Exploratory analysis
- Visualization
- Clear and honest conclusions

---

## Research Questions

The analysis focuses on the following questions:

1. How does a movie’s budget relate to its revenue?
2. Which genres generate the highest average revenue?
3. How has average movie revenue changed over time?
4. Do movies with higher audience ratings tend to earn more revenue?

---

## Dataset

- Source: The Movie Database (TMDb)
- Rows: ~10,000 movies
- Each row represents a single movie
- Revenue and budget values are adjusted for inflation (2010 USD)

---

## Tools & Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Key Analysis Steps

- Removed movies with invalid or missing financial data
- Focused on inflation-adjusted budget and revenue for fair comparison
- Explored relationships using scatter plots, bar charts, and line plots
- Used helper functions to improve code readability and reduce repetition

---

## Key Insights

- Movies with higher budgets tend to generate higher revenue, though exceptions exist.
- Adventure, Science Fiction, and Fantasy genres show higher average revenue.
- Average movie revenue has generally increased over time.
- Higher-rated movies tend to earn more revenue, but ratings alone do not guarantee success.

---

## Limitations

- The dataset does not include marketing or promotional costs.
- Many movies belong to multiple genres, making genre attribution complex.
- This analysis is exploratory and descriptive; it does not imply causation.

---

## Repository Structure
tmdb-movie-revenue-analysis/
│
├── Investigate_a_Dataset.ipynb
├── Investigate_a_Dataset.html
├── tmdb-movies.csv
└── README.md


---

## Author

Ayush Pandey


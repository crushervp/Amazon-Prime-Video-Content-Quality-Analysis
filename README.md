# Amazon Prime Video Content Quality Analysis

Exploratory data analysis of the Amazon Prime Video catalogue, focusing on content quality, ratings, and catalogue strategy using Python (Pandas, Matplotlib, Seaborn) with 15+ visual insights.

---

## Project Overview

This project analyzes the Amazon Prime Video titles dataset to understand what kinds of content dominate the platform and how quality indicators such as IMDb and TMDb ratings vary by genre, country, and release year.  
The goal is to derive actionable insights that can inform content acquisition, production, and recommendation strategy.

Key questions explored include:
- How is the catalogue distributed across movies vs TV shows?
- Which genres and countries contribute most to the library?
- How do IMDb and TMDb ratings vary across genres and over time?
- Which titles, people, and regions stand out in terms of perceived quality?

---

## Dataset

The analysis uses two CSV files:

- `titles.csv` – Metadata about each title (type, genre(s), release year, runtime, ratings, etc.).
- `credits.csv` – Cast and crew information linked to titles.

These files are loaded directly into the notebook and joined where needed for deeper insights on people (actors, directors, etc.).

---

## Methods and Tools

The analysis is implemented in a single Jupyter/Colab notebook:

- `Amazon_Prime_EDA.ipynb`

Main Python libraries used:
- `pandas` for data loading, cleaning, joining, and feature engineering
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for visualization

Core steps:
1. Load and inspect the raw data.
2. Clean and preprocess (handle missing values, convert data types, engineer helper columns).
3. Perform univariate and bivariate analysis on key features (type, genre, country, ratings, year).
4. Join titles and credits to explore cast/crew patterns.
5. Build 15+ charts to visually answer the problem statement questions.
6. Summarize findings into clear, data-driven insights.

---

## Key Insights

Some of the insights derived in the notebook include:

- The catalogue is skewed towards certain dominant **genres**, while niche genres are underrepresented.  
- Ratings show clear variation across **genres** and **countries**, indicating where viewer-perceived quality is strongest or weakest.  
- Recent years exhibit shifts in both the **volume** of content released and the distribution of ratings, hinting at evolving content strategies.  
- Certain **actors/directors** appear frequently in higher-rated content, suggesting valuable creative partnerships.

(For full details, see the “Insights” and “Conclusion” sections inside the notebook.)

---

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/crushervp/Amazon-Prime-Video-Content-Quality-Analysis.git
   cd Amazon-Prime-Video-Content-Quality-Analysis

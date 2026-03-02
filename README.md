# 📊 Amazon Prime Video Content Quality Analysis

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)](https://matplotlib.org/)

> Exploratory data analysis of the Amazon Prime Video catalogue with **15+ visual insights** on content quality, ratings, and strategic recommendations using Python.

---

## 🎯 Problem Statement

Amazon Prime Video needs data-driven insights to optimize its content catalogue. This project analyzes **what kinds of content dominate the platform**, **how quality varies by genre and region**, and **which content strategies drive higher viewer ratings**. The goal is to inform acquisition, production, and recommendation strategies.

---

## 📈 Project Overview

This exploratory data analysis answers key business questions:

- **Distribution**: How is the catalogue split between movies and TV shows?
- **Genre Trends**: Which genres and countries contribute most to the library?
- **Quality Patterns**: How do IMDb and TMDb ratings vary across genres, countries, and years?
- **Top Performers**: Which titles, actors, and regions stand out in perceived quality?
- **Temporal Insights**: Are there shifts in content strategy or quality over time?

---

## 🗂️ Dataset

The analysis uses two CSV datasets:

| File | Description | Records |
|------|-------------|----------|
| `titles.csv` | Metadata (type, genres, year, runtime, ratings, etc.) | ~9,600+ titles |
| `credits.csv` | Cast and crew information linked to titles | ~100,000+ credits |

These datasets are joined to analyze patterns in cast, crew, and production quality.

---

## 🛠️ Tools & Methods

**Core Libraries:**
- **Pandas** – Data loading, cleaning, transformation, and feature engineering
- **NumPy** – Numerical operations and calculations
- **Matplotlib & Seaborn** – Publication-quality visualizations

**Methodology:**
1. ✅ Load and inspect raw data
2. ✅ Clean and preprocess (missing values, data types, feature engineering)
3. ✅ Univariate analysis (distributions, summaries)
4. ✅ Bivariate & multivariate analysis (correlations, relationships)
5. ✅ Create 15+ charts with clear insights
6. ✅ Synthesize findings into actionable recommendations

---

## 🔍 Key Insights (Sample)

- 🎬 **Genre Dominance**: Certain genres (Drama, Comedy, Action) account for 60%+ of the catalogue, while niche genres are underrepresented.
- ⭐ **Quality Variance**: Ratings show significant variation across genres and countries, revealing which regions produce the highest-rated content.
- 📅 **Temporal Shift**: Recent years show changes in release patterns and rating distributions, suggesting evolving content strategies.
- 🎭 **Creative Partnerships**: Certain actors and directors appear in disproportionately high-rated content.
- 🌍 **Regional Strengths**: Specific countries excel in particular genres, offering targeted acquisition opportunities.

**→ Full insights and visualizations available in the notebook.**

---

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)

1. Upload `Amazon_Prime_EDA.ipynb` to [Google Colab](https://colab.research.google.com/)
2. Upload `titles.csv` and `credits.csv` to Colab
3. Run cells in order from top to bottom

### Option 2: Local Jupyter Notebook

```bash
# Clone the repository
git clone https://github.com/crushervp/Amazon-Prime-Video-Content-Quality-Analysis.git
cd Amazon-Prime-Video-Content-Quality-Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook Amazon_Prime_EDA.ipynb
```

**Prerequisites:**
- Python 3.8+
- Jupyter or Google Colab
- CSV data files in the same directory

---

## 📁 Repository Structure

```
.
├── Amazon_Prime_EDA.ipynb          # Main analysis notebook with all visualizations
├── titles.csv                      # Titles metadata (9,600+ rows)
├── credits.csv                     # Cast & crew information (100,000+ rows)
├── README.md                       # This file
└── .gitignore                      # Standard Python gitignore
```

---

## 📊 Visualizations Included

The notebook contains **15+ charts** covering:

- Pie charts: Content type distribution (Movies vs TV Shows)
- Bar charts: Top genres, top countries, ratings by genre
- Histograms: Rating distributions across platforms
- Line plots: Ratings trends over years
- Heatmaps: Genre-Country correlations
- Scatter plots: Runtime vs ratings relationships
- Top 10 tables: Best-rated titles, actors, directors by genre

---

## 🎓 Learning Outcomes

This project demonstrates:

✅ End-to-end exploratory data analysis workflow  
✅ Data cleaning and feature engineering with Pandas  
✅ Effective data visualization for storytelling  
✅ Business insight extraction from large datasets  
✅ Writing reusable, well-documented Python code  

---

## 🔮 Future Enhancements

- 📱 Build an interactive dashboard (Streamlit/Plotly)
- 🤖 Implement a content recommendation system using similarity metrics
- 🔗 Compare analysis across multiple streaming platforms
- 📈 Time-series forecasting for upcoming content trends
- 🎯 Clustering analysis to identify content niches

---

## 📝 License

This project is created for educational and portfolio purposes.

The dataset source and usage terms: [Check original dataset documentation]

---

## 👤 Author

**Vidyadhar Patil** ([@crushervp](https://github.com/crushervp))

Bengaluru, India | Data Analyst & Python Developer

---

## 🤝 Contributing

Feedback and suggestions are welcome! Feel free to:

- 🐛 Report issues
- 💡 Suggest improvements
- 🔀 Submit pull requests

---

**⭐ If you found this helpful, please consider starring the repository!**

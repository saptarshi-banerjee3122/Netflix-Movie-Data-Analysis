# 🎬 Netflix Movie Data Analysis

##  Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on a Netflix movie dataset to uncover patterns related to movie genres, ratings, popularity, audience engagement, release trends, and overall movie performance.

The analysis combines data cleaning, feature engineering, statistical exploration, visualization, and advanced analytical techniques to derive meaningful insights from the dataset.

---

## Project Objectives

* Analyze movie genre distribution.
* Explore rating and popularity patterns.
* Understand audience engagement through vote counts.
* Identify trends across release years and decades.
* Discover hidden gems with strong ratings but low popularity.
* Create a custom success score to evaluate movie performance.
* Generate business insights from analytical findings.

---

##  Dataset

**Dataset Name:** `mymoviedb.csv`

The dataset contains information related to Netflix movies, including:

* Title
* Genre
* Release Date
* Vote Average (Rating)
* Vote Count
* Popularity
* Original Language
* Other movie-related attributes

---

##  Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Project Workflow

### 1. Data Understanding

* Loaded and explored the dataset.
* Inspected dataset structure and feature information.
* Generated summary statistics.

### 2. Data Cleaning & Preprocessing

* Handled missing values.
* Checked and removed duplicate records.
* Standardized column names.
* Converted release dates to datetime format.
* Extracted release year information.
* Created decade-based features.

### 3. Exploratory Data Analysis (EDA)

* Genre Analysis
* Rating Analysis
* Popularity Analysis
* Vote Count Analysis
* Language Analysis
* Release Year Analysis
* Correlation Analysis

### 4. Data Visualization

* Bar Plots
* Histograms
* Scatter Plots
* Heatmaps
* Pairplots
* KDE Plots
* Boxplots
* Countplots
* Lineplots

### 5. Advanced Analysis

* Hidden Gems Analysis
* Success Score Analysis
* Most Successful Movies
* Most Popular Movie of Each Year
* Highest Rated Movie of Each Genre
* Top Years by Average Rating
* Overrated Movies Analysis
* Outlier Detection using IQR
* Skewness Analysis
* Log Transformation Analysis
* Rating Category Analysis
* Popularity Category Analysis

### 6. Business Insights & Conclusion

* Generated business-oriented insights from the analysis.
* Summarized findings through a final conclusion.

---

##  Key Analyses Performed

* Genre Distribution Analysis

* Rating Distribution Analysis

* Popularity Distribution Analysis

* Popularity vs Rating Relationship

* Vote Count Analysis

* Release Year Trend Analysis

* Decade-wise Movie Analysis

* Language-based Performance Analysis

* Correlation Analysis

* Hidden Gems Detection

* Success Score Evaluation

* Outlier Detection

* Skewness Analysis

* Log Transformation Comparison

* Rating Categorization

* Popularity Categorization

* Overrated Movies Identification

---

## 📈 Visualizations

The project includes multiple visualizations such as:

* Top Genres
* Movies Released Per Year
* Rating Distribution
* Popularity Distribution
* Correlation Heatmap
* Popularity vs Rating Scatter Plot
* Language Distribution
* Top Rated Movies
* Most Popular Movies
* Vote Count Analysis
* Hidden Gems Analysis
* Success Score Analysis

Screenshots of important visualizations can be found inside the **images/** folder.

---

##  Key Findings

* A small number of genres dominate the movie catalog.
* Most movies receive moderate to high audience ratings.
* Popularity is concentrated among a relatively small number of titles.
* Highly popular movies are not always the highest rated.
* Several high-quality movies remain underexposed despite strong ratings.
* Movie success depends on multiple factors rather than a single metric.
* Audience engagement varies significantly across movies and genres.

---

##  Repository Structure

```text
Netflix Movie Data Analysis/
│
├── images/
├── mymoviedb.csv
├── README.md
└── requirements.txt
├── netflix_analysis.ipynb
```

---

## ▶ How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```text
netflix_analysis.ipynb
```

5. Run all cells sequentially.

---

##  Business Value

This analysis demonstrates how data-driven approaches can support:

* Content recommendation systems
* Audience preference analysis
* Content acquisition strategies
* Movie performance evaluation
* Decision-making for streaming platforms

---

##  Author

**Saptarshi Banerjee**



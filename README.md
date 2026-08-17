# 🎬 Netflix Data Analysis & Visualization

An Exploratory Data Analysis (EDA) and data visualization project on the Netflix Movies and TV Shows dataset using Python in Google Colab.

---

## 🎯 Objective

* Perform Exploratory Data Analysis (EDA) on streaming platform data
* Extract features from dates, runtimes, cast lists, and geographic locations
* Visualize distributions, seasonality, and cast networks using static and geospatial charts

---

## 📊 Dataset

* File: `netflix_titles.csv`
* Features:
  * `show_id` (Unique Identifier)
  * `type` (Movie or TV Show)
  * `title` (Content Title)
  * `director` (Director Names)
  * `cast` (Cast Members)
  * `country` (Production Countries)
  * `date_added` (Platform Addition Date)
  * `release_year` (Original Release Year)
  * `rating` (Age Rating)
  * `duration` (Runtime or Seasons)
  * `listed_in` (Genres)
  * `description` (Plot Summary)

---

## 📈 Exploratory Data Analysis (EDA)

* Content Type Breakdown (Bar & Pie Charts)
* Top Content Producing Countries (Horizontal Bar Chart)
* Age Rating Distributions (Bar Chart)
* Release Year Trends & Movie Runtimes (Histplot & KDE)
* Content Addition Seasonality (Heatmap)
* Plot Summaries Word Cloud (Text Mining)
* Prolific Directors & Featured Actors (Bar Charts)
* Actor Co-Occurrences & Duos (Network Pair Analysis)
* Genre Distribution Proportions (Treemap)
* Global Content Concentration (Choropleth World Map)

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud
* Squarify
* Google Colab

---

## 🚀 Workflow

1. Install geospatial and text modeling dependencies (`geopandas`, `wordcloud`, `squarify`)
2. Load dataset with `latin1` fallback encoding
3. Preprocess missing values, parse date columns, and extract numeric runtimes
4. Explode multi-valued string columns (`country`, `listed_in`, `director`, `cast`)
5. Generate static charts, heatmaps, treemaps, and geospatial world map

---

## 🤖 Key Insights

* **Content Ratio:** Movies represent ~70% of the Netflix library, while TV Shows make up ~30%.
* **Top Producers:** United States, India, and United Kingdom lead global content volume.
* **Duration:** Median movie runtime sits around 98 minutes.
* **Seasonality:** Fourth quarter (Q4) months consistently see higher platform content additions.

---

## 📊 Results

* Cleaned and transformed complex comma-separated string columns without data loss
* Successfully rendered 10 distinct visualization blocks optimized for Google Colab
* Generated a full-scale geospatial heat map mapping global entertainment production

---

## 🔮 Future Improvements

* Integrate external movie ratings via IMDb and Rotten Tomatoes APIs
* Build an interactive Web Dashboard using Streamlit or Dash
* Perform Sentiment Analysis and Topic Modeling on plot descriptions

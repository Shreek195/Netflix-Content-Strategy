# Netflix Content Strategy – Exploratory Data Analysis

## Overview
Exploratory data analysis of Netflix’s content catalog to understand platform strategy across content type, genres, countries, ratings, and release timing.

## Dataset
- ~7,700 Netflix titles
- Types: Movies & TV Shows
- Key fields: type, country, genre, rating, duration, date_added, release_year

## Key Insights
- Netflix library is **movie-heavy (~70%)**
- Rapid content growth between **2016–2019**, followed by slowdown
- **United States** dominates content production, followed by **India**
- Content is primarily targeted at **mature audiences** (TV-MA, TV-14)
- Most movies are **80–120 minutes**, most TV shows have **1 season**
- Netflix balances **new originals** with a large catalog of older licensed content

## Feature Engineering
- Year & month added
- Content age when added to Netflix
- Parsed genres, countries, durations

## Visual Analysis
- Content growth over time
- Genre and country distribution
- Duration patterns for movies and TV shows
- Rating trends
- Word cloud and common phrase analysis from descriptions

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, WordCloud, Scikit-learn

# Netflix Data Analysis

## Project Overview

This project analyzes Netflix's catalog of Movies and TV Shows using Python and Pandas. The objective is to identify trends in content production, genre distribution, country-wise contribution, and platform growth.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

Netflix Movies and TV Shows Dataset from Kaggle.

## Features

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Exploratory Data Analysis (EDA)
- Data Visualization
- Trend Analysis

## Key Insights

- Movies dominate Netflix's content library.
- The United States contributes the highest amount of content.
- Netflix content growth accelerated after 2015.
- Drama is one of the most popular genres.

## Visualizations

- Movies vs TV Shows
- Top 10 Countries
- Top Genres
- Content Added by Year

## Final Architecture

                    NETFLIX ANALYSER

┌───────────────────────────────────────┐
│          Netflix Dataset (.csv)       │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│          Data Ingestion Layer         │
│ • Load CSV using Pandas               │
│ • Read and validate data              │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│         Data Cleaning Layer           │
│ • Handle missing values               │
│ • Remove duplicates                   │
│ • Standardize formats                 │
│ • Convert date columns                │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│      Feature Engineering Layer        │
│ • Extract release year                │
│ • Genre separation                    │
│ • Content categorization              │
│ • Country extraction                  │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│      Exploratory Data Analysis        │
│ • Movies vs TV Shows                  │
│ • Genre trends                        │
│ • Country-wise analysis               │
│ • Year-wise growth                    │
│ • Ratings distribution                │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│        Visualization Engine           │
│ • Bar Charts                          │
│ • Pie Charts                          │
│ • Line Graphs                         │
│ • Heatmaps                            │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│         Insight Generation            │
│ • Trend Identification                │
│ • Content Distribution Insights       │
│ • Business Recommendations            │
└───────────────────┬───────────────────┘
                    │
                    ▼
┌───────────────────────────────────────┐
│             Final Output              │
│ • Dashboard/Notebook                  │
│ • Visual Reports                      │
│ • Data-driven Conclusions             │
└───────────────────────────────────────┘
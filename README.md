# Netflix Shows Data Analysis

This project involves analyzing the Netflix Titles dataset (`netflix_titles.csv`). The dataset contains information about Netflix shows, including titles, directors, cast, country of production, release year, and genres. The analysis focuses on understanding trends in release years, genre popularity, and content production by country.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [Analysis Steps](#analysis-steps)
  - [Data Loading](#data-loading)
  - [Data Cleaning](#data-cleaning)
  - [Simple Analysis](#simple-analysis)
  - [Visualization](#visualization)
- [Results](#results)
  - [Shows Released Per Year](#shows-released-per-year)
  - [Most Common Genres](#most-common-genres)
  - [Top Content-Producing Countries](#top-content-producing-countries)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

This project provides insights into the Netflix Shows dataset, focusing on identifying trends in the number of shows released per year, the most common genres, and the top countries producing content.


## Analysis Steps

### 1. Data Loading
- The dataset is loaded using Pandas and explored to understand its structure and content.

### 2. Data Cleaning
- Missing values in the `director`, `cast`, and `country` columns are filled with "Unknown".
- Rows with missing `date_added`, `rating`, and `duration` are dropped.

### 3. Simple Analysis
- **Number of Shows Released Each Year**: Counts the number of shows released per year.
- **Most Common Genres**: Splits and counts the genres listed for each show.
- **Top 10 Countries Producing the Most Content**: Identifies and counts the countries producing content.

### 4. Visualization
- Simple visualizations are created using Matplotlib:
  - A bar chart for the top 10 most common genres.
  - A bar chart for the top 10 content-producing countries.

## Results

### Shows Released Per Year
- Provides a distribution of the number of shows released each year, useful for understanding trends over time.

### Most Common Genres
- Identifies and visualizes the top 10 genres in the Netflix catalog, showing the most prevalent types of content.

### Top Content-Producing Countries
- Highlights the top 10 countries producing the most content on Netflix, showcasing global contributions to the platform.

## Conclusion
This analysis provides a basic overview of the Netflix Shows dataset, offering insights into release trends, genre popularity, and content production by country.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib

## Installation

To get started with this project, you'll need to install the required dependencies. You can do this using pip:

```bash
pip install pandas numpy matplotlib




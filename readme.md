# IMDb Movies India Dataset Analysis

This project involves analyzing a dataset of Indian movies listed on IMDb. The aim is to clean the data, analyze it to find the year with the best average rating, explore the relationship between movie duration and rating, and visualize these findings.

## Project Overview

The IMDb Movies India dataset contains information about various Indian movies, including their year of release, duration, genre, ratings, votes, and more. This analysis cleans the data by handling missing values and incorrect formats, calculates the year with the highest average rating, examines the correlation between movie duration and IMDb rating, and visualizes the findings.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Libraries: Pandas, Numpy, Matplotlib, Seaborn

### Installation

Ensure Python is installed on your machine. Then, install the required Python libraries using pip:

```sh
pip install pandas numpy matplotlib seaborn
```

### Data Cleaning
The dataset undergoes several cleaning steps, including:

Extracting the year from the Year column and converting it to a float.
Removing "min" from the Duration column and converting it to a float.
Converting Rating and Votes to floats, filling missing values with the mean, and cleaning non-numeric characters from Votes.

### Analysis
Year with the Best Average Rating: Identify which year had the highest average IMDb rating.
Correlation Analysis: Determine if there's a significant correlation between the length of the movie and its IMDb rating.

### Visualizations
Movie Duration vs. IMDb Rating Scatter Plot: Visualize the relationship between movie duration and IMDb rating to identify any patterns or correlations.

### Running the Analysis
Update the file_path variable in the script to point to the location of your IMDb Movies India dataset.
Run the Python script to perform the data cleaning, analysis, and visualizations.

### Conclusion
This project provides insights into the IMDb ratings of Indian movies, highlighting the year with the best average rating and exploring the impact of movie duration on ratings. The visualizations and analysis help in understanding trends within the dataset.

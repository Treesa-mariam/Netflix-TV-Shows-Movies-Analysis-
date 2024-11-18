# Netflix-TV-Shows-Movies-Analysis-
This project provides a comprehensive analysis of Netflix's extensive catalog of TV shows and movies, leveraging a dataset obtained from Flixable, a third-party Netflix search engine, which is freely available on Kaggle. The goal was to uncover trends, patterns, and insights into the content available on Netflix to better understand its offerings.

**Project Highlights
Dataset Overview:**

The dataset comprises 7789 rows and 11 columns, featuring details like show ID, category (TV show or movie), title, director, cast, country, release date, rating, duration, type, and description.
Initial exploration included viewing the data's first and last few rows, shape, size, column names, and data types using Pandas functions like head(), tail(), shape, size, columns, dtypes, and info().

**Data Cleaning and Preparation:**

Duplicate records were identified using the duplicated() function and removed using drop_duplicates().
Null values were analyzed using isnull() and visualized with a Seaborn heatmap.
Converted and formatted date-related columns for further analysis.

****Key Analytical Insights:**

*'House of Cards' Information: Extracted the show ID and director of the flagship show.
*Year with the Most Releases: Identified the year with the highest number of releases, visualized using a bar chart.
*Content Distribution: Created a count plot to visualize the distribution between movies and TV shows.
*Exclusive Releases: Identified TV shows exclusively available in India.
*Top Directors: Analyzed and listed the top 10 most featured directors on Netflix.
*Content Types by Region: Focused on comedies or releases exclusive to the UK.
*Celebrity Insights: Counted the number of titles featuring Tom Cruise.
*Ratings Distribution: Created a pie chart to display the share of different Netflix ratings.
*Longest Content: Identified the content with the maximum duration.
*Top Country for TV Shows: Analyzed which country has the highest number of TV shows.
*Sorted Dataset: Arranged the dataset by release year for chronological insights.

**Content Trends Over Time:**

Performed a time series analysis to examine how the number of Netflix releases changed over the years using a line plot.
Conducted a month-wise analysis to identify peak content release months, highlighting seasonal trends in Netflix's content distribution.

**Visualizations:**

Country-wise Distribution: Created a choropleth map to visualize geographical distribution.
Ratings: Showcased the distribution of Netflix ratings using a pie or donut chart.
Release Trends: Line plots and bar charts to show annual and monthly trends.

**Content Length Analysis:
**
For movies, categorized durations into "Short Film," "Feature Film," and "Epic Film."
For TV shows, calculated the average number of seasons and analyzed the distribution of seasons.

**Tools & Libraries Used**

Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly
Visualization: Matplotlib, Seaborn, and Plotly for interactive and static visualizations
Data Source: Dataset sourced from Kaggle

**Outcome**

This project provides meaningful insights into Netflix's content strategy, including its global footprint, release trends, and catalog diversity. The visualizations and analyses offer a clear, data-driven perspective on Netflix's vast content library, helping users understand trends and patterns in the entertainment industry.


# STC-Jawwy-TV-Data-Analysis

#Overview

This project analyzes the STC Jawwy TV dataset, which includes user activity data on movies and TV shows, with details such as program genre, viewing duration, and video quality (HD vs SD). The goal is to extract key insights about user behavior, content popularity, and the impact of program quality on engagement.

#Dataset Description

The dataset contains metadata about programs (movies and series), user activity logs, and viewing details.

#Key columns include:

program_name, program_class (Movie or Series/Episodes)

program_genre

user_id_maped (user identifier)

duration_seconds

hd (quality flag: 1 for HD, 0 for SD)

date_ (viewing date)

Season and episode numbers for series content

Data Preprocessing
Removed unnecessary columns and trimmed whitespace from program names.

Converted date and numeric columns to appropriate data types.

Handled missing values and ensured consistency in string columns.

Analysis Tasks
Top Programs by Total Watch Time

Calculated total unique users, views, and watch time.

Distinguished episodes by season and episode number.

Identified top 10 programs with highest engagement.

User Behavior by Program Type

Compared movies vs series on metrics like total watch time and unique users.

Visualized data with scatter plots and pie charts.

Impact of Video Quality (HD vs SD)

Analyzed user engagement by program quality.

Compared HD and SD viewing patterns for movies and series.

Calculated HD share of total views and watch time.

Genre-wise Analysis by Quality

Compared user counts for HD vs SD within each program genre.

Visualized differences with bar charts.

Key Findings
HD content has a significant share of total views and watch time, especially for movies.

Series episodes tend to have more consistent watch time across HD and SD.

Some genres have higher user preference for HD, influencing content delivery strategies.

Top programs dominate user engagement, suggesting targeted content investment.

Visualizations
Pie charts showing watch time distribution among top programs and by program type.

Scatter plots relating number of users to total watch time.

Bar charts comparing HD vs SD user counts per genre.

Interactive charts created with Plotly for detailed exploration.

How to Run
Load the Excel dataset using Pandas.

Preprocess the data as shown.

Run the analysis scripts sequentially for insights.

Visualize results using Matplotlib, Seaborn, and Plotly.

Requirements
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Plotly

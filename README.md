# YouTube Trending Video Analysis
Overview
This project performs an exploratory data analysis (EDA) on YouTube trending video data to uncover insights related to video performance, viewer engagement, and trending patterns. The analysis covers a range of metrics, including views, likes, dislikes, and comments, across various video categories.

# Project Objectives
Analyze Trends: Identify trends and patterns in YouTube trending videos over time.
Visualize Data: Use visual tools to present insights on video performance and engagement.
Categorical Insights: Determine which video categories and channels perform the best.
Textual Analysis: Examine common keywords in video titles and descriptions.

# Data
The dataset used for this analysis includes the following columns:

video_id: Unique identifier for each video.
trending_date: Date when the video appeared on the trending list.
title: Title of the video.
channel_title: Name of the channel that uploaded the video.
category_id: ID representing the category of the video.
publish_time: Time when the video was published.
tags: Tags associated with the video.
views: Number of views the video received.
likes: Number of likes the video received.
dislikes: Number of dislikes the video received.
Key Analysis and Insights
Distribution of Views and Engagement:

Visualized the distribution of views, likes, and dislikes across trending videos.
Used matplotlib and seaborn for creating histograms and scatter plots.
Category Performance:

Analyzed average views per category and identified the top-performing categories.
Visualized category performance using bar charts.
Channel Trends:

Identified channels with the most trending videos.
Created visualizations to compare channel performance over time.
Like-to-Dislike Ratio:

Calculated and visualized the ratio of likes to dislikes for each video.
Identified videos with the highest and lowest ratios.
Publish Time Analysis:

Analyzed the distribution of publish times (hours of the day) and their impact on trending status.
Used time series plots to examine trends.
Textual Analysis:

Generated a word cloud from video titles to identify common keywords and content trends.
Used WordCloud library for textual visualization.
Tools and Libraries
Python: Programming language used for data analysis.
pandas: Data manipulation and analysis.
matplotlib & seaborn: Visualization of data.
WordCloud: Generation of word clouds from textual data.

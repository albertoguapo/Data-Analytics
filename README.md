# Personal Spotify Streaming Data Analysis

This repository contains an analysis of my personal Spotify streaming history. The project focuses on exploring my listening habits, track preferences, and other behavioral insights from the data extracted from my Spotify account.

## Project Overview

The goal of this project is to:
- Clean and transform the raw streaming data.
- Analyze key trends in listening time, most played tracks, albums, and artists.
- Investigate how my listening patterns vary across different devices, locations, and modes.
- Provide insights into user behavior such as shuffle and offline listening preferences.

## Data Structure

The dataset includes the following columns:
- **Date and Time**: The date and time when the track was played.
- **Streaming Device**: The device used to stream (e.g., mobile, desktop).
- **Listening Time (Minutes)**: Total listening time for each track, measured in minutes.
- **Connection Country**: The country from which the connection was made.
- **Track Name**: Name of the track that was played.
- **Album Artist**: The artist of the album containing the track.
- **Album Name**: The name of the album the track is from.
- **Shuffle Enabled**: Whether shuffle mode was enabled (Yes/No).
- **Skipped**: Whether the track was skipped (Yes/No).
- **Offline Listening**: Whether the track was played offline (Yes/No).
- **Incognito Mode**: Whether incognito mode was enabled (Yes/No).

## Analysis and Insights

This project includes the following analyses:
- **Top Tracks and Artists**: Identifying the most played songs and favorite artists.
- **Listening Time Analysis**: Analyzing patterns in total listening time over different periods (daily, weekly, monthly).
- **Device and Mode Insights**: Investigating how the choice of device and playback mode (shuffle, offline) affects my listening experience.
- **Geographical Trends**: Analyzing the connection countries and their influence on listening habits.

## Technologies Used
- Python
- pandas
- Jupyter Notebooks (for data analysis)
- Excel (for data cleaning and transformation)
- Matplotlib (for data visualization)
- Seaborn (for statistical data visualization)
- WordCloud (for generating word clouds)

## License
This project is for personal use only. No commercial use is permitted.

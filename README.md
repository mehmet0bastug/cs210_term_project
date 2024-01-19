# cs210 Term Project Mehmet Barış Baştuğ
# YouTube Watch History Analysis

## Overview
This project analyzes an individual's YouTube watch history to gain insights into their viewing habits. The analysis focuses on categorizing videos into education, entertainment, and music, and examines changes in viewing patterns across different days and times, particularly around exam periods.

## Features
- Parsing YouTube watch history from an HTML file.
- Categorizing videos into education, entertainment, and music.
- Analyzing viewing habits on weekdays vs. weekends.
- Examining viewing patterns during exam periods.
- Calculating average daily video consumption in each category.

## Data
The data for this project is extracted from a YouTube watch history HTML file. This includes details such as video name, channel name, and the time when the video was watched.

## Usage
1. **Data Extraction**: The script `parse_html_and_write_csv.py` reads the YouTube watch history from an HTML file and converts it into a CSV format for easier analysis.
2. **Data Analysis**: The data is analysed.
3. **Visualization**: The script includes matplotlib and seaborn-based visualizations to provide insights into viewing habits.

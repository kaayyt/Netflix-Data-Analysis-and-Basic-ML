# Netflix Data Analysis Project

This project focuses on performing an **Exploratory Data Analysis (EDA)** on Netflix's content dataset. The analysis explores various aspects of the content available on Netflix, such as content types, genres, ratings, and other interesting insights. The goal is to uncover trends and patterns in Netflix's content offerings, allowing users to gain valuable insights into the platform's catalog.

## Project Overview

The project involves a comprehensive data analysis of Netflix’s dataset, focusing on the following steps:

### 1. **Data Upload and Cleaning**
   - **CSV File Upload**: The user is prompted to upload a CSV file containing Netflix content data.
   - **Data Cleaning**: 
     - Removal of any duplicate rows.
     - Handling of missing values by dropping rows with missing critical data (e.g., director, cast, or country).
     - Conversion of the `date_added` column to a proper datetime format for analysis.

### 2. **Exploratory Data Analysis (EDA)**
   The analysis covers the following key aspects of the dataset:

   - **Content Type Distribution**: 
     - Identifies and visualizes the distribution of content between Movies and TV Shows.
   
   - **Genre Analysis**:
     - Extracts and visualizes the top 10 most common genres across all content available on Netflix.

   - **Content Added Over Time**: 
     - Analyzes and visualizes the trends in content added over the years, identifying peaks and declines in content releases.

   - **Top Directors**:
     - Identifies and visualizes the top 10 directors with the most titles on Netflix, providing insights into the most prolific filmmakers on the platform.

   - **Movie Title Word Cloud**:
     - Generates a word cloud based on movie titles to visualize the most common words in the titles of movies on Netflix.

   - **Rating Analysis**:
     - Analyzes and visualizes the distribution of content ratings across Movies and TV Shows, highlighting the frequency of different ratings.

   - **Top Countries**:
     - Identifies the top 10 countries with the most content on Netflix and visualizes the distribution across these countries.

### 3. **Visualizations**
   The project generates several types of visualizations to present the insights gained from the data:
   - **Bar Charts**: To visualize the distribution of content types, genres, and top directors.
   - **Pie Charts**: To show the rating distribution for Movies and TV Shows.
   - **Word Cloud**: A graphical representation of the most common words in movie titles.
   - **Line Plots**: To track content additions over time, helping to visualize trends in Netflix's content library.

## Key Insights and Findings
Through this analysis, the project highlights various insights such as:
- The most popular content types (Movies vs. TV Shows).
- The most frequent genres and countries of origin for Netflix's content.
- Trends in content additions over the years.
- Insights into directors and the popularity of different ratings across Movies and TV Shows.

## How to Use
1. **Upload a CSV file** containing the Netflix dataset when prompted by the script.
2. The script will automatically clean the dataset by handling missing values, dropping duplicates, and converting the date column.
3. The analysis will run, and the results will be visualized in the form of charts and plots, giving you insights into various aspects of Netflix's content.

## Requirements
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static visualizations.
- `seaborn`: For statistical data visualization and advanced plotting.
- `wordcloud`: For generating word clouds from movie titles.
- `google.colab`: For file upload functionality when running the code in Google Colab.

## Conclusion
This project provides an in-depth view of Netflix's content catalog, helping to identify trends, popular genres, and content distribution over time. By performing this analysis, we gain a better understanding of Netflix's offerings and the platform's content strategy.

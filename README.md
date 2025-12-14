 ### Amazon Prime TV Shows and Movies Analysis.
 
### Problem Statement:
 This project aims to explore and analyze a dataset of movies and TV shows to identify key trends, patterns, and relationships between various attributes such as release year, genre, runtime, production country, and audience reception (IMDb and TMDb scores). The goal is to gain a comprehensive understanding of the content landscape and potentially uncover factors that contribute to the popularity and reception of titles.

### Data Description (Summary)

*   **Total Entries:** The dataset contains 124,347 entries.
*   **Columns:** There are 19 columns with various details about titles and people.
*   **Content Identification:** Each title has a unique `id`, `title`, `type` (Movie/Show), `description`, and `release_year`.
*   **Human Involvement:** `person_id`, `name`, `character`, and `role` detail the individuals involved.
*   **Content Characteristics:** `runtime` (minutes), `genres` (list of genres), `production_countries` (list of countries), `age_certification`, and `seasons` (for TV shows) describe the content.
*   **Audience Metrics:** `imdb_id`, `imdb_score`, `imdb_votes`, `tmdb_popularity`, and `tmdb_score` provide insights into popularity and critical reception.
*   **Missing Data Handled:** Missing values in numerical columns (`imdb_score`, `imdb_votes`, `tmdb_popularity`, `tmdb_score`) were filled with means. `seasons` (for movies) was filled with 0. Other categorical missing values (`character`, `description`, `age_certification`, `imdb_id`) were filled with 'Unknown'.
*   **Data Types:** Mix of integers, floats, and objects (strings/lists).
*   **Key Relationships:** There's a strong correlation between IMDb score and votes, and a moderate one between IMDb and TMDb scores.

### Data Exploration Insights

*   **Content Types:** There are many more movies than TV shows in the dataset.
*   **Popular Genres:** 'Drama', 'Comedy', and 'Thriller' are the most common movie and TV show types.
*   **Content Growth:** The number of new movies and TV shows released each year has grown a lot, especially since the early 2000s, with a peak around 2019.
*   **Content Lengths:** Movies usually run for about 90-100 minutes. TV show episodes are much shorter.
*   **Age Ratings:** Many titles don't have an age rating recorded. Among those that do, 'R', 'PG-13', and 'PG' are common.
*   **Production Hubs:** The United States produces by far the most content, followed distantly by the UK, India, and Canada.
*   **Review Scores:** IMDb and TMDb scores generally agree; if a title gets a high score on one, it often does on the other too.
*   **Runtime vs. Score:** While there's a slight tendency for longer runtimes to have higher IMDb scores, runtime alone isn't a strong predictor of quality.
*   **Scores Over Time:** The average IMDb score has stayed fairly consistent over the years, but the average TMDb popularity has been increasing, especially recently.
*   **Age Rating & Scores:** The typical IMDb scores vary across different age certifications, with some categories like 'G' and 'TV-Y' appearing to have higher median scores than others like 'R'.
*   **Movie vs. Show Scores:** Movies and TV shows have similar typical IMDb scores.
*   **TV Show Seasons:** Most TV shows have only a few seasons (often just one), with fewer shows continuing for many years.
*   **Variable Relationships:** IMDb scores and votes are strongly linked. IMDb and TMDb scores also have a moderate connection, as do IMDb votes and TMDb popularity.
  
### Project Approach Steps

*   Problem Definition
*   Data Loading and Initial Inspection
*   Missing Value Analysis
*   Data Wrangling
*   Exploratory Data Analysis (EDA) and Visualization
*   Insight Extraction and Storytelling
*   Solution Formulation
*   Conclusion
     
###  Learning Outcomes
 Upon completing this project,  I understand how to systematically explore real-world datasets, clean messy information, and use visualizations to uncover trends in content like movies and TV shows. They will learn to identify relationships between variables such as genre, runtime, and audience scores, and translate these data-driven insights into practical business recommendations, fostering a deep understanding of exploratory data analysis techniques.

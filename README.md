# netflixandchill
Project 1 - Netflix and Disney+ data analysis with OMDB API

## Project Description:
Our project aims to analyze and compare the content offerings, IMDB ratings, budgets, and subscription prices of Netflix and Disney+ between 2019-2021. We will address the research question: Does Netflix or Disney+ have higher  rated content? In addition to IMDb ratings, we will analyze content types and genres, trends in release years, and subscription prices. We will utilize datasets containing Netflix and Disney+ titles and metadata along with the OMDB API for ratings and streaming service price data. Through this project, we hope to gain insight into the evolving landscape of streaming services and their content strategies.

## Research Questions to Answer:
    1.	Does Netflix or Disney+ have higher quality rated content?
    2.	How does the composition of content type (i.e. movies and TV shows) differ between Netflix and Disney+ over the period 2019-2021?
    3.	Do the release patterns reflect any strategic shifts or content acquisition strategies for each platform?
    4.	How have the subscription prices of Netflix and Disney+ changed over the period 2019-2021?

## Task Breakdown:
    1.	Create Git repository, permission access to group members, save initial CSV datasets to repository folder.
    2.	In Jupyter Notebook, load CSV datasets into pandas, Create DataFrames.
    3.	Transform, clean the data as needed, including filter out non-relevant information, handle missing values, date types conversion and data parsing.
    4.	Concatenate the Netflix and Disney+ DataFrames.
    5.	Call OMDB API to collect ratings metadata for all titles, Create columns and pull API metadata into DataFrame. API key(s) must be created for this task.
    6.	Use pandas functions to group data into aggregated or summarizes tables, create new DataFrames from aggregation for further analysis.
    7.	Build visualizations to highlight data for conclusion points and answering research questions.
    8.	Write complete analysis based on findings and create presentation for class.

## Sources
### Netflix Movies & TV Shows list:
    Dataset Title: Disney Movies & TV Shows
    Author: Shivam Bansal
    Source: Kaggle
    URL: https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows?select=disney_plus_titles.csv
    
### Disney Movies & TV Shows list:
    Dataset Title: Netflix Shows
    Author: Shivam Bansal
    Source: Kaggle
    URL: https://www.kaggle.com/datasets/shivamb/netflix-shows?select=netflix_titles.csv
    
### OMDb API:
    OMDb API is a free web service to obtain movie information.
    URL: http://www.omdbapi.com/
### Streaming service prices:
    Dataset Title: Streaming Service Prices
    Author: WebDevBadger
    Source: Kaggle
    URL: https://www.kaggle.com/datasets/webdevbadger/streaming-service-prices

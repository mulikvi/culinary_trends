# Cuisine Compass

This repository contains the below objects :

1) Culinary Trends.twbx : Tableau dashboard to display last 7 days’ trending recipes and categories from Reddit
2) DAG BigQuery.py : This code orchestrates the execution of two Google Cloud Functions using Apache Airflow: one for web scraping (web_scraping) and another for loading data from a Cloud Storage bucket to BigQuery (load_file_from_bucket_to_bigquery). The pipeline starts, triggers both functions sequentially, and then ends.
3) Data Preprocessing.ipynb : Used for pre processing data.
4) Data Transformations.py : This code reads CSV files from a specified Google Cloud Storage bucket, processes the files to extract dish names and a creation date, and then loads the processed data into a BigQuery table.
5) FoodNames Extraction.py : This code generates a sequence of outputs by using Langchain to process a list of cuisines and generate food-related data.
6) KNN Recipe Recommender.ipynb : Find recipes based on nutritional values and to recommend similar recipes using KNN
7) RecipeDAG.py  : This code sets up an Apache Airflow DAG to import a CSV file from Google Cloud Storage into BigQuery, and then execute a SQL query on the data to filter and clean it.
8) Reddit Scrape.py : This script retrieves and processes comments from a specific Reddit post using the praw (Python Reddit API Wrapper) library and Pushshift.io API
9) Web Scrapper.py : This script scrapes Reddit post titles from a specific subreddit, processes them to extract food-related names using an AI model, and uploads the cleaned data to Google Cloud Storage
10) Regression Analysis and ML.ipynb  
11) SQL Queries.sql
12) main.py
13) requirements.txt

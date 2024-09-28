# IMDB Ratings Scraper

This project is a simple web scraping tool designed to collect and visualize movie ratings from the IMDB website. The aim of this project was to practice web scraping techniques and work with data from a well-known source.

## Overview

The script scrapes the IMDB website for movie ratings from the past 10 years and plots a distribution of the ratings. The visualization is basic, focusing primarily on practicing data extraction and web scraping skills.

## Features

Scrapes movie ratings for films released over the last 14 years.
Simple visualization of the distribution of ratings using Python's data visualization libraries.
Clean, straightforward code designed to focus on the essentials of web scraping.

## Technologies Used

Python: Core language for scripting.
BeautifulSoup: To parse HTML and extract data from the IMDB website.
Requests: For sending HTTP requests to IMDB and retrieving web pages.
Matplotlib/Seaborn: For visualizing the distribution of ratings.

## How It Works

The script accesses the IMDB website and collects data on movie ratings from the last decade.
The collected data is then processed, extracting relevant fields such as movie titles, release dates, votes, and ratings.
A distribution plot of the ratings is generated to provide a visual representation of the dataset.

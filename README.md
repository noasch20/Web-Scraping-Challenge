# Mars Data Scraping and Analysis

## Overview
  This repository contains two Jupyter Notebooks designed to scrape, process, and analyze data related to Mars. The first notebook extracts news article titles and previews from a Mars news website, while the second notebook scrapes and analyzes Mars weather data from a static HTML table.

## Part 1: Scraping Mars News

## Objective
  
  Extract the latest news article titles and previews from the Mars News website.
## Steps
  
  Use automated browsing with Selenium to visit the Mars News website.
  
  Parse the webpage using Beautiful Soup to identify and extract the relevant HTML elements.
 
  Store each article's title and preview text in a dictionary with keys title and preview.
  
  Store all extracted data in a list of dictionaries.

## Part 2: Scraping and Analyzing Mars Weather Data

## Objective
  
  Scrape weather data from a Mars Temperature Data website and analyze key trends.

## Steps
  
  Use automated browsing with Selenium to navigate to the weather data page.
  
  Use Beautiful Soup to scrape data from an HTML table containing Mars temperature records.
  
  Store the extracted data in a Pandas DataFrame with the following columns:
    id: Transmission ID from Curiosity rover
    terrestrial_date: Earth date
    sol: Martian day count since Curiosity's landing
    ls: Solar longitude
    month: Martian month
    min_temp: Minimum temperature in Celsius
    pressure: Atmospheric pressure at Curiosity’s location
 
  Convert data to appropriate types (datetime, int, float) for analysis.
  
  Answer questions regarding monthly minimum temperature, monthly atmospheric pressure, and year length.
  
  Export the cleaned dataset as a CSV file.

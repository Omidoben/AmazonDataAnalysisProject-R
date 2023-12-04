
# Amazon Sales Data Cleaning and Exploratory Analysis Project


## Overview

This project focuses on the comprehensive data cleaning and exploratory analysis of raw Amazon sales data. The goal is to transform the initial dataset into a usable format and derive meaningful insights that can facilitate decision-making.
## Tools

- R, R Studio
- R Markdown
## Libraries Used

- Tidyverse, Skimr, Cowplot, knitr, kableExtra
## Data Cleaning Process

### Data Preparation
- Loaded the necessary libraries
- Imported the data into R
- Checked data types, structure of variables, null values and duplicates

### Data Cleaning
- I created a new data frame that contains variables to be used in this analysis
- Changed data types of some columns to numeric, stripped newline characters (discounted_price, actual_price, and discounted_percentage)
- Filled in missing values
- Split category column into two (Also fixed the strings in this newly created columns)


## Exploratory Data Analysis

- Created a table to display the distribution of porducts by category and sub category
- Used a bar plot to visualize distribution of products by main category and subcategory (Some categories had a small count of products; less than 5, thus, I combined this small categories to enable easy visualization and meaningful comparisons)
- Checked whether there exists relationships between some columns. Also performed a correlation test.
- Used histograms to check the distribution of variables
- Utilised box plots to explore the distribution of Rating column under different product categories.
- Created a new categorical column; rating_score, to determine the overall customer's satisfaction for the products.

## Interpretation and Insights

- Based on our dataset, Electronic products commands the highest sales, followed closely by Computer Accessories products.
- Office products had the highest median ratings, implying that they were the most highly rated products by the customers.
- The data strongly supports the hypothesis that the higher the price of a product is, the higher the discount given.
-  63% of the customers were “very satisfied” by the products, 35% were “Satisfied”, and only 0.6% were “Unsatisfied”. This indicates that products supplied by Amazon are of great quality.

### Note

While this analysis offers valuable insights, it is important to note that the dataset was recorded 10 months ago.

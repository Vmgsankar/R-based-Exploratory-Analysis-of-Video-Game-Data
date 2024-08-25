# Exploratory Data Analysis (EDA) of Video Game Sales

Welcome to the Exploratory Data Analysis (EDA) of Video Game Sales! This project uses the `vgsales` dataset to analyze video game sales across different regions, genres, and platforms. The analysis includes data cleaning, descriptive statistics, and bivariate analysis to uncover insights into sales trends and relationships.

## Table of Contents

- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Descriptive Analysis](#descriptive-analysis)
- [Bivariate Analysis](#bivariate-analysis)
- [Insights](#insights)
- [Key Recommendations](#key-recommendations)
- [Installation](#installation)

## Introduction

The goal of this project is to perform an exploratory analysis on the `vgsales` dataset, which contains information about global video game sales across different regions. The dataset includes sales data in North America, Europe, Japan, and other regions, as well as global sales and attributes such as genre, platform, and publisher. By analyzing these attributes, we aim to uncover trends and patterns in video game sales.

## Data Cleaning

Data cleaning is an essential step to ensure the accuracy and reliability of the analysis. This project involves the following data cleaning steps:
- **Missing Values**: Identifying and handling missing values to prevent bias in the analysis.
- **Data Types**: Ensuring that data types are correctly assigned for accurate analysis.
- **Outliers**: Identifying and addressing outliers that may skew results.

## Descriptive Analysis

Descriptive analysis provides a summary of the dataset's main characteristics. Key areas of focus include:
- **Distribution of Sales by Region**: Examining the distribution of video game sales across different regions, such as North America, Europe, and Japan.
- **Sales by Genre and Platform**: Analyzing total sales figures based on game genres and platforms.
- **Sales Over Time**: Investigating global sales trends across different years.
- **Correlation Analysis**: Evaluating the correlation between sales in different regions to understand their relationships.

## Bivariate Analysis

Bivariate analysis explores the relationships between two variables. This project includes:
- **Scatter Plots**: Visualizing the relationship between global sales and regional sales to identify any patterns or correlations.
- **Stacked Bar Charts**: Analyzing how global sales are distributed across genres and platforms, showing the combined effects of these factors.

## Insights

- **Regional Sales Trends**: North American sales have shown the highest distribution compared to other regions, indicating a strong market presence in North America.
- **Genre Popularity**: Certain genres consistently achieve higher global sales, highlighting their popularity across different regions.
- **Platform Preferences**: Some platforms dominate global sales, suggesting successful and preferred gaming platforms among consumers.
- **Sales Over Time**: Global sales trends may show growth or decline over the years, potentially correlated with significant industry events or game releases.
- **Correlation**: Strong correlations between regional sales suggest that regional markets significantly impact global sales.

## Key Recommendations

- **Focus on Popular Genres**: Game developers and publishers should prioritize genres that consistently show high sales figures.
- **Invest in High-Selling Platforms**: Platforms with the highest global sales should be the focus for game development and marketing strategies.
- **Regional Strategies**: Tailor marketing and sales strategies based on regional sales trends to enhance market penetration.
- **Monitor Sales Trends**: Regularly analyze sales trends to adapt to market changes and evolving consumer preferences.

## Installation

To run this project locally, install the required R packages using the following commands:

```r
install.packages("ggplot2")
install.packages("dplyr")
install.packages("readr")
install.packages("ggcorrplot")

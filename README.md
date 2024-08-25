# Exploratory Data Analysis (EDA) of Video Game Sales

Welcome to the Exploratory Data Analysis (EDA) of Video Game Sales! This project leverages the `vgsales` dataset to analyze video game sales across different regions, genres, and platforms. The analysis covers data cleaning, descriptive statistics, and bivariate analysis to provide insights into sales trends and relationships.

## Table of Contents

- [Introduction](#introduction)
- [Data Loading](#data-loading)
- [Data Cleaning](#data-cleaning)
- [Descriptive Analysis](#descriptive-analysis)
- [Bivariate Analysis](#bivariate-analysis)
- [Insights](#insights)
- [Key Recommendations](#key-recommendations)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

The purpose of this project is to conduct an exploratory analysis on the `vgsales` dataset, which includes global video game sales data across various regions. This dataset contains sales information for North America, Europe, Japan, and other regions, as well as attributes such as genre, platform, and publisher. By exploring these attributes, we aim to uncover trends and patterns in video game sales.

## Data Loading

To start with the analysis, you need to load the necessary R libraries and the dataset:

```r
# Load necessary libraries
library(ggplot2)
library(dplyr)
library(readr)
library(ggcorrplot)

# Load the dataset
vgsales <- read_csv("/path/to/your/vgsales.csv")

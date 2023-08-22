# Project Title: Crash Incidence Analysis for The State of Victoria - [FINTECH USE CASE]

## Overview

This project involves utilizing the Python programming language and its dependencies namely Pandas, Numpy,hvplot, among others, to analyse and gain understanding from a dataset obtained from Victorian government websites. The main goal of the project is to apply what we have studied and learned as of date. These include Python, Pandas, Jupyter Lab, APIs, and other dependencies and functionalities. These are applied to clean and preprocess the data, perform analysis, and eventually come up with meaningful insights from the final dataset.

## Table of Contents

Introduction
Dataset Description
Project Steps
 - Data loading
 - Data Cleaning and Wrangling
 - Data Analysis
Conclusion
Dependencies/Libraries
Usage

### Introduction

In data wrangling and manipulation purposes where the main works involve tabular data, Pandas provide very powerful tools such as DataFrame and Series. It makes cleaning messy data sets easier and convert them to become readable and meaningful. This project showcases the said practical uses of Pandas as we applied it in data cleaning, trasformation, aggregation, and visualisation.

### Dataset Description

The dataset used in this project consists of data that we extracted from https://dtp.vic.gov.au/about/data-and-research/vista/vista-data-and-publications and https://www.bitre.gov.au/statistics/safety/fatal_road_crash_database. These are mainly tables in csv forms that include accident event, accident chainage, accident location, accident, atmospheric condition, metadata, person, road surface, statistics checks, vehicle. These dataset being in their raw forms have NaN, missing values, duplicates that need to be resolved.

### Data Loading

The initial step is to import each tables and load them into DataFrame. The read_csv and Path functions are used to read the tables. Other steps taken are previewing the DataFrame to ensure data has been loaded correctly, and identifying the number of rows and columns in the DataFrame.

### Data Cleaning and Wrangling

Under this step, the NaN, zero, and null values are resolved using functions such as .dropna(), .fillna(), etc. The data are also validated by comparing the column extracted against the original file, specifically, tallying the columns and row counts.

### Data Analysis

It involves examining the data to gain insights and identify patterns. Using Pandas, the below operations are done:

Summary statistics (mean, sum, media, linear regression, etc.)
Locations analysis (frequency of accidents, number of deaths)
Segmentation (age, gender, etc. of the victims)
Visualisations (line plots, bar charts) using libraries like hvplot, GeoViews, Matplotlib together with Pandas.

Based on the data Analysis, we derived insights such as identifying the likelihood of a vehicle accident in an area, death occuring from the accident, relationship between persons killed in an accident and light condition, and the likes.   
### Conclusion

Through this project, we've demonstrated how to use Pandas and other libraries for analyzing raw datasets and turn it around into a very informative one. The intuitive syntax and powerful functionalities make it an essential tool for data manipulation and analysis tasks.

### Dependencies/Libraries

Python 3.10
Pandas
Numpy
Pathlib
Matplotlib (for visualizations)

### Usage

Clone the project repository from GitHub.
Install the required dependencies using pip/conda installs.
Upload the datasets in the appropriate directory.
Run the Jupyter notebook or Python script to execute the project steps.
By completing this project, we have gained valuable experience in using Pandas, etc., to clean, explore, and derive insights from real-world data. 




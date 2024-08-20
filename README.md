# Data Wrangling and Exploratory Data Analysis (EDA)

## Overview
This repository contains two Jupyter Notebooks that focus on processing and analyzing data stored in various fomrats. They are intended to demonstrate essential data handling techniques such as reading files, transforming data structures, and preliminary analysis to extract insights from structured data.

## Features
- **Data Transformation**: Parse complex JSON structures and convert them into Pandas DataFrames.
- **File Inspection**: Evaluate file sizes and content, including basic line counts and data previews.
- **Exploratory Data Analysis**: Use Pandas functions to explore data through head and tail methods, as well as key inspection in JSON and CSV objects.
- **Advanced Data Merging and Cleaning**: Detailed merging and data cleaning operations to prepare datasets for comprehensive analysis.
- **Log Parsing**: Techniques for extracting date and time information from log files using regular expressions.

## Usage
- Ensure all prerequisites are installed.
- Open the notebooks in Jupyter Lab or Jupyter Notebook.
- Run the cells sequentially to observe data wrangling and Exploratory Data Analysis steps across different data types and formats.

## Prerequisites
- Python 3.x
- Pandas library
- Numpy library
- OS module for operating system interactions
- JSON module for JSON file handling
- `re` module for regular expression operations

## Input
- `restaurants.tsv`: A TSV file containing data about restaurants.
- `confirmed-cases.json`: A JSON file detailing COVID-19 confirmed cases.
- `county_and_state.csv`: CSV file with county and state data.
- `county_and_population.csv`: CSV file detailing populations per county.

## Output
- DataFrames containing processed restaurant data and COVID-19 cases.
- Merged and cleaned data from multiple CSV files.
- Outputs displaying file sizes, line counts, and preliminary data views.
- Insights derived from detailed exploratory data analysis.

## Notes
- Adjust the paths according to your local directory structure if necessary.
- The notebooks are designed for basic to intermediate data handling and may need modifications to handle other types of data or more complex scenarios.
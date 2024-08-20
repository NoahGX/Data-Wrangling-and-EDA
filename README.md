# Data Wrangling and Exploratory Data Analysis (EDA)

## Overview
This repository contains a Jupyter Notebook that focuses on processing and analyzing data stored in TSV and JSON formats, demonstrating essential data handling techniques such as: reading files, transforming data structures, and preliminary analysis to extract insights from structured data.

## Features
- **Data Importing**: Load data from both TSV and JSON files.
- **Data Transformation**: Parse complex JSON structures and convert them into Pandas DataFrames.
- **File Inspection**: Evaluate file sizes and content, including basic line counts and data previews.
- **Exploratory Data Analysis**: Use Pandas functions to explore data through head and tail methods, and key inspection in JSON objects.

## Usage
- Ensure all prerequisites are installed.
- Open the notebook in Jupyter Lab or Jupyter Notebook.
- Run the cells sequentially to observe data wrangling and Exploratory Data Analysis steps.

## Prerequisites
- Python 3.x
- Pandas library
- Numpy library
- OS module for operating system interactions
- JSON module for JSON file handling

## Input
- `restaurants.tsv`: A TSV file containing data about restaurants.
- `confirmed-cases.json`: A JSON file detailing COVID-19 confirmed cases.

## Output
- A DataFrame containing restaurant data.
- A DataFrame created from COVID-19 cases data.
- Outputs displaying file sizes, line counts, and preliminary data views.

## Notes
- Adjust the paths according to your local directory structure if necessary.
- The notebook is basic and may need modifications to handle other types of data or more complex scenarios.
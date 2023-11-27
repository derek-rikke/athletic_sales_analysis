# athletic_sales_analysis
Module 5 Challenge

```markdown
# Athletic Sales Analysis

## Overview

This repository contains Python code for analyzing athletic sales data. The data is sourced from two CSV files, `athletic_sales_2020.csv` and `athletic_sales_2021.csv`. The code utilizes the pandas library for data manipulation and analysis.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Analysis Steps](#analysis-steps)
    - [Combine and Clean the Data](#1-combine-and-clean-the-data)
    - [Determine which Region Sold the Most Products](#2-determine-which-region-sold-the-most-products)
    - [Determine which Region had the Most Sales](#3-determine-which-region-had-the-most-sales)
    - [Determine which Retailer had the Most Sales](#4-determine-which-retailer-had-the-most-sales)
    - [Determine which Retailer Sold the Most Women's Athletic Footwear](#5-determine-which-retailer-sold-the-most-womens-athletic-footwear)
    - [Determine the Day with the Most Women's Athletic Footwear Sales](#6-determine-the-day-with-the-most-womens-athletic-footwear-sales)
    - [Determine the Week with the Most Women's Athletic Footwear Sales](#7-determine-the-week-with-the-most-womens-athletic-footwear-sales)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To run this code, make sure you have Python installed. Additionally, install the required dependencies using the following command:

```bash
pip install pandas
```

## Usage

Run the Python script in your preferred environment. Make sure to have the CSV files, `athletic_sales_2020.csv` and `athletic_sales_2021.csv`, in the `Resources` directory.

```bash
python your_script.py
```

## Analysis Steps

### 1. Combine and Clean the Data

The code reads two CSV files, `athletic_sales_2020.csv` and `athletic_sales_2021.csv`, into separate DataFrames and then combines them.

### 2. Determine which Region Sold the Most Products

Utilizing groupby and pivot_table, the code determines the total number of products sold for each region, state, and city.

### 3. Determine which Region had the Most Sales

Similar to the previous step, this part of the analysis focuses on total sales for each region, state, and city.

### 4. Determine which Retailer had the Most Sales

The code identifies the retailer with the highest total sales, considering region, state, and city.

### 5. Determine which Retailer Sold the Most Women's Athletic Footwear

Filtering the data for women's athletic footwear, the code identifies the retailer with the highest sales in this category.

### 6. Determine the Day with the Most Women's Athletic Footwear Sales

The analysis focuses on identifying the specific day with the highest total sales for women's athletic footwear.

### 7. Determine the Week with the Most Women's Athletic Footwear Sales

Building on the previous step, this analysis zooms out to identify the week with the highest total sales for women's athletic footwear.

## Contributing

Feel free to contribute to this project. Open an issue or submit a pull request with any improvements or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).

written by ChatGPT
```

Please replace "your_script.py" with the actual name of your Python script containing the provided code. Also, ensure to include a proper license file (`LICENSE`) in your repository.

written by ChatGPT

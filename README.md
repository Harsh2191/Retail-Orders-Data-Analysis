# Retail Orders Data Analysis

## Project Overview

This project involves the analysis of retail order data to derive business insights. The workflow includes data extraction, preprocessing, loading into SQL Server, and executing SQL queries for analysis.

## Project Flow

1. **Data Extraction & Preprocessing:**
   - Download retail order data from Kaggle.
   - Handle missing values and rename columns.
   - Derive new columns for profit calculations.
   - Convert date formats for consistency.

2. **Data Loading:**
   - Establish a connection to SQL Server using SQLAlchemy.
   - Load the processed data into the SQL Server for structured storage.

3. **Data Analysis:**
   - Execute various SQL queries to extract insights such as:
     - Top 10 highest revenue-generating products.
     - Top 5 highest selling products in each region.
     - Month-over-month sales growth for 2022 and 2023.
     - Category-wise monthly highest sales.
     - Sub-category with highest growth in profit for 2023 compared to 2022.

## Setup Instructions

### Prerequisites

- Python 3.x
- SQL Server
- Kaggle API key

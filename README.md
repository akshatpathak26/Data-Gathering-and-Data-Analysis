# Pandas Data Analysis Notebooks

This repository contains Jupyter notebooks demonstrating pandas functionality for data import, manipulation, analysis, and export.

## Notebooks

### pandas-import.ipynb

- Importing pandas
- Reading Excel files
    - Specifying sheet name
    - Setting index column
- Reading text files
    - Using sep parameter for tabs

### pandas-export.ipynb  

- Exporting DataFrames
    - to CSV
        - Example aggregations before exporting
    - to Excel 
        - Specifying sheet names
        - Writing multiple sheets
    - to HTML
    - to JSON
    - to SQL 
        - Using SQLAlchemy engine
        - Appending and overwriting DataFrames 

### working-with-SQL-and-JSON-data.ipynb

- Reading JSON files
    - Local and remote URLs
- Loading data from MySQL database
    - Using mysql-connector-python
    - Writing queries 

### working-with-csv.ipynb

- Reading from local CSVs
- Reading CSVs from URLs
- Parameter guides
    - sep
    - index_col
    - header  
    - usecols
    - squeeze
    - skiprows/nrows
    - encoding
    - parse_dates
    - converters
    - na_values
    - chunksize

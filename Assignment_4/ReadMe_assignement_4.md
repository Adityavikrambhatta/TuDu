# Python File Handling Project

This project demonstrates various file handling operations in Python, including writing, reading, appending, and error handling with text files. It also includes mini-projects for sales data analysis and product information management.

## Table of Contents
1.  [Task 1: Write Sales Records to a File](#task-1-write-sales-records-to-a-file)
2.  [Task 2: Read File in Different Ways](#task-2-read-file-in-different-ways)
3.  [Task 3: Append New Sales](#task-3-append-new-sales)
4.  [Task 4: Generate Summary Report from File](#task-4-generate-summary-report-from-file)
5.  [Task 5: Create Product Info File (User Input)](#task-5-create-product-info-file-user-input)
6.  [Task 6: Read File Safely (Error Handling)](#task-6-read-file-safely-error-handling)
7.  [Task 7: Mini Project - Export Discounted Prices](#task-7-mini-project---export-discounted-prices)

## Project Overview
This Colab notebook explores fundamental file I/O operations using Python. Each task builds upon basic concepts to perform more complex operations, such as data processing, reporting, and interactive file creation.

### Task 1: Write Sales Records to a File
This task involves creating a text file (`sales_data.txt`) and writing a list of sales figures to it, with each sale on a new line. An optional task (`sales_data_1.txt`) demonstrates writing sales figures separated by commas.

### Task 2: Read File in Different Ways
Demonstrates various methods to read content from `sales_data.txt`:
-   `file.read()`: Reads the entire content of the file.
-   `file.readline()`: Reads a single line from the file.
-   `file.readlines()`: Reads all lines into a list of strings, which are then converted to integers.

### Task 3: Append New Sales
This section shows how to read existing sales data from `sales_data.txt`, append new sales figures to the list, and then overwrite the file with the updated, combined sales data, separated by commas.

### Task 4: Generate Summary Report from File
This task defines several functions to calculate key sales metrics (total sales, average sales, highest sale, lowest sale) from the `sales_data.txt` file and prints a summary report.

### Task 5: Create Product Info File (User Input)
This interactive task prompts the user to input product names and prices. This information is then formatted and written to a new file named `products.txt`, with each product and its price separated by a pipe (`|`).

### Task 6: Read File Safely (Error Handling)
Illustrates how to incorporate error handling (using `try-except` blocks) when opening and reading a file. It prompts the user for a file name and gracefully handles cases where the specified file does not exist.

### Task 7: Mini Project - Export Discounted Prices
This mini-project calculates discounted prices for a given set of products. It prompts the user for a discount percentage, applies it to a dictionary of original product prices, and then writes a report (`discount_report.txt`) containing original and discounted prices. It also calculates and prints the total number of items and the average discounted price.

## Files Created/Used
-   `sales_data.txt`: Stores sales figures.
-   `sales_data_1.txt`: An alternative sales data file (optional).
-   `products.txt`: Stores product names and prices entered by the user.
-   `discount_report.txt`: Contains a report of original and discounted product prices.

## How to Use
To use this project, simply open the Colab notebook and run the cells sequentially. You will be prompted for input in Task 5 and Task 7. The output for each task will be displayed within the notebook cells.
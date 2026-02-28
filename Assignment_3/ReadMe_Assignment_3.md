# Assignment 3: Functions (User-Defined, Recursive, Lambda, Map, Filter)

This notebook demonstrates various types of functions in Python through a series of tasks.

## Task 1 - Basic Function: `PriceAfterDiscount`

- Defines a user-defined function `apply_discount` to calculate the price of a product after applying a discount. It includes a default discount percentage and a boundary condition check for the maximum discount.

## Task 2 - Recursive Function: `Factorial Utility`

- Implements a recursive function `factorial` to calculate the factorial of a given number, handling positive, zero, and negative inputs.

## Task 3 - Lambda Function: `GST Calculator`

- Introduces a `lambda` function `gst` to calculate the price of an item after adding an 18% Goods and Services Tax (GST). An optional example combining GST and discount is also included.

## Task 4 - Using `map()`: Apply GST to List of Prices

- Demonstrates the use of the `map()` function to apply the `gst` lambda function to every item in a list of `prices`, generating a new list with GST-inclusive prices.

## Task 5 - Using `filter()`: Filter Expensive Products

- Illustrates how to use the `filter()` function with a `lambda` expression to extract products from a list that are considered 'expensive' (prices greater than 500).

## Task 6 - Combined Utility Functions

- Creates a `process_prices` function that combines `map()` and `filter()` to perform two operations simultaneously: calculating discounted prices (10% off) and filtering prices greater than 300 from a given list.

## Task 7 - Mini Problem: Menu Using Functions

- Presents an interactive menu-driven program that allows a user to manage a list of prices. It uses several helper functions (`add_price`, `max_price`, `averages` lambda) to perform operations like adding prices, calculating the average price, and finding the maximum price.

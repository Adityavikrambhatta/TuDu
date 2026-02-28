{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "# Assignment 3: Functions (User-Defined, Recursive, Lambda, Map, Filter)\n",
        "\n",
        "This notebook demonstrates various types of functions in Python through a series of tasks.\n",
        "\n",
        "## Task 1 - Basic Function: `PriceAfterDiscount`\n",
        "\n",
        "- Defines a user-defined function `apply_discount` to calculate the price of a product after applying a discount. It includes a default discount percentage and a boundary condition check for the maximum discount.\n",
        "\n",
        "## Task 2 - Recursive Function: `Factorial Utility`\n",
        "\n",
        "- Implements a recursive function `factorial` to calculate the factorial of a given number, handling positive, zero, and negative inputs.\n",
        "\n",
        "## Task 3 - Lambda Function: `GST Calculator`\n",
        "\n",
        "- Introduces a `lambda` function `gst` to calculate the price of an item after adding an 18% Goods and Services Tax (GST). An optional example combining GST and discount is also included.\n",
        "\n",
        "## Task 4 - Using `map()`: Apply GST to List of Prices\n",
        "\n",
        "- Demonstrates the use of the `map()` function to apply the `gst` lambda function to every item in a list of `prices`, generating a new list with GST-inclusive prices.\n",
        "\n",
        "## Task 5 - Using `filter()`: Filter Expensive Products\n",
        "\n",
        "- Illustrates how to use the `filter()` function with a `lambda` expression to extract products from a list that are considered 'expensive' (prices greater than 500).\n",
        "\n",
        "## Task 6 - Combined Utility Functions\n",
        "\n",
        "- Creates a `process_prices` function that combines `map()` and `filter()` to perform two operations simultaneously: calculating discounted prices (10% off) and filtering prices greater than 300 from a given list.\n",
        "\n",
        "## Task 7 - Mini Problem: Menu Using Functions\n",
        "\n",
        "- Presents an interactive menu-driven program that allows a user to manage a list of prices. It uses several helper functions (`add_price`, `max_price`, `averages` lambda) to perform operations like adding prices, calculating the average price, and finding the maximum price."
      ],
      "metadata": {
        "id": "G4yIvTO7pops"
      }
    }
  ]
}
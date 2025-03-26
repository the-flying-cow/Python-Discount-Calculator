# Python-Discount-Calculator
This Python script calculates the final price of an item after applying a discount (if applicable).

## Features
- Takes user input for the original price and discount percentage.
- Applies the discount only if it is 20% or higher.
- Returns the final price or the original price (if no discount is applied).

## Usage
 - Run the script in a Python environment:
 - Enter the discount percentage (e.g., 25).
 - The script will output either:
    - The discounted price (if discount ≥ 20%), or
    - The original price (if discount < 20%).

## Code Overview
- Function: calculate_discount(price, discount_percent)
   - Applies discount logic and returns the final price.
- Input Handling:
   - Uses float(input()) to accept decimal values.
- Output Formatting:
  - Prices are displayed with 2 decimal places (e.g., $24.99).

## Requirements
- Python 3.x
  

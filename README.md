# WEEK_THREE_PLP_PYTHON
# Discount Calculation for Prices

## Overview
This Python script calculates the final price of an item after applying a discount. If the discount percentage is **20% or higher**, the discount is applied. Otherwise, the original price remains unchanged.

## Features
- User-friendly input prompts
- Handles invalid inputs gracefully
- Applies discount only when it's **20% or more**
- Displays the final price with **two decimal places**

## Usage
1. Run the script in a Python environment.
2. Enter the original price of the item when prompted.
3. Enter the discount percentage.
4. View the calculated final price.

## Code Overview
The program defines a function:

def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (price * discount_percent / 100)
    else:
        return price
The function checks if the discount is at least 20%.

If true, it applies the discount and returns the new price.

Otherwise, it returns the original price.

## Example Run
Enter the original price of the item: 100
Enter the discount percentage: 25
The final price after applying the discount is: 75.00

## Error Handling
- If the user enters non-numeric values, the script displays:  
  `"Invalid input. Please enter numeric values."`

## Implementation
The discount is calculated using:
```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (price * discount_percent / 100)
    else:
        return price

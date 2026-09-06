# Shopping Cart Management System

## Overview

The Shopping Cart Management System is a beginner-friendly Python console application that allows users to manage products in a shopping cart and calculate the final bill.

The program supports adding products, removing products, changing quantities, applying discounts, and calculating GST.

## Features

- Add products to the cart
- Remove products from the cart
- Change product quantity
- View the cart
- Calculate subtotal
- Apply a discount percentage
- Apply 18% GST
- Display the final bill
- Exit the application

## Requirements

- Python 3.x
- No external libraries are required

## How to Run

1. Install Python 3.x.
2. Save the program as `shopping_cart.py`.
3. Open a terminal or command prompt.
4. Run:

```bash
python shopping_cart.py
```

## Menu Options

| Option | Description |
|---|---|
| 1 | Add Product |
| 2 | Remove Product |
| 3 | Change Quantity |
| 4 | View Cart |
| 5 | Apply Discount & GST |
| 6 | Exit |

## Billing Calculation

The program calculates the bill in the following order:

1. Calculate the subtotal of all products.
2. Calculate the discount.
3. Subtract the discount from the subtotal.
4. Calculate 18% GST on the discounted amount.
5. Add GST to get the final amount.

### Formula

```text
Subtotal = Product Price × Quantity

Discount = Subtotal × Discount Percentage / 100

Price After Discount = Subtotal - Discount

GST = Price After Discount × 18 / 100

Final Amount = Price After Discount + GST
```

## Example

```text
Laptop     ₹50000 × 1
Mouse      ₹1000 × 2
Keyboard   ₹2000 × 1

Subtotal = ₹54000

Discount = 10%
Discount Amount = ₹5400

Price After Discount = ₹48600

GST = 18%
GST Amount = ₹8748

Final Amount = ₹57348
```

## Concepts Used

- Variables
- Dictionaries
- Functions
- `if/elif/else`
- `while` loops
- `for` loops
- User input
- Arithmetic operations
- Formatted output

## Project Type

**Python Console Application**

## Learning Objective

This project is useful for learning how Python can be used to build a simple real-world billing and cart management system.

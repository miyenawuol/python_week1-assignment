# Python Program: Total Cost Calculator

This program asks the user for the price of one item and the quantity they want to buy, then calculates and displays the total cost.

```python
# Prompt user for price and quantity
price_str = input("Enter the price of one item: ")
quantity_str = input("How many items do you want? ")

# Convert inputs to float and int
price = float(price_str)
quantity = int(quantity_str)

# Calculate total
total = price * quantity

# Print friendly summary
print(f"{quantity} items at {price:.2f} each = {total:.2f}")
```

## Example Output

```text
Enter the price of one item: 25.50
How many items do you want? 3
3 items at 25.50 each = 76.50
```

This code works by converting the user input into numbers before doing the multiplication, so the total is calculated correctly.
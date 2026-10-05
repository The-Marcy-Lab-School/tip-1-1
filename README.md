# tip-1-1

#### Task: Cafe Receipt Generator

Write a program that calculates and formats an itemized receipt for a customer order.

**Requirements:**

1. Define variables for `item_name` (string), `unit_price` (float or int), and `quantity` (int).
2. Calculate `subtotal` and a 10% `tax` amount.
3. Display output using all three approaches: comma-separated `print()` statements, concatenated string formatting requiring explicit `str()` conversions, and print statements with an f-string
4. Output must clearly display data without crashing.

**Sample Output** 

This assumes that an item called “Coffee” costs $4.50 and the customer orders 3 

```python
Item purchased: Coffee | Quantity: 3
Subtotal: $13.5
Tax (10%): $1.35
Final Amount Due: $14.85
```

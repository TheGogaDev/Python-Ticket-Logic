# Cinema Ticket Validator 🎟️

A logic-based Python script that determines user eligibility, pricing, and discounts for a cinema booking system.

## 🚀 Key Programming Concepts
* **Conditional Logic**: Extensive use of `if-elif-else` structures to handle different user scenarios.
* **Logical Operators**: Combining conditions using `and`, `or`, and `not` to create complex rules.
* **Nested Conditionals**: Implementing service charges only after a booking condition is satisfied.
* **State Management**: Tracking variables like `extra_charges` and `discount` based on user attributes.

## 💻 Logic Highlight: Complex Eligibility
The script features a sophisticated eligibility check that considers age, showtime, and membership status in a single expression:
```python
if age >= 21 or age >= 18 and (show_time != 'Evening' or is_member):
    # Proceed with booking...

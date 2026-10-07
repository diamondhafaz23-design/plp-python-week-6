# Python Exception Handling Assignment

This project demonstrates robust error handling in Python using `try-except` blocks. It provides safe wrapper functions to prevent common runtime crashes like dividing by zero, parsing invalid data types, or looking up missing keys in a dictionary.

## Features

The script contains three core functions designed to handle specific exceptions gracefully:

1. **`safe_divide(a, b)`**
   * **Purpose:** Divides two numbers.
   * **Exception Handled:** `ZeroDivisionError` (catches attempts to divide by zero and returns a custom string message).

2. **`safe_number(text)`**
   * **Purpose:** Converts a string input into an integer.
   * **Exception Handled:** `ValueError` (catches invalid string conversions and returns a warning message).

3. **`get_field(learner, key)`**
   * **Purpose:** Safely retrieves a value from a dictionary.
   * **Exception Handled:** `KeyError` (catches missing dictionary keys and returns a "Field not found" status).

## Usage & Expected Output

When you run the script, it executes several test cases to demonstrate the error-handling behavior:

```python
# Run the script using Python 3
python main.py
```

### Console Output:
```text
5.0
Cannot divide by zero
42
Not a number
82
Field not found
```

## Requirements
* Python 3.x

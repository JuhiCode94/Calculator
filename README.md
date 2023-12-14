# Calculator Application

This is a simple calculator application implemented in Python using the PyQt6 library. The calculator supports basic arithmetic operations, percentage calculations, and parentheses balancing.

## Features

### Basic Arithmetic Operations
- Addition (+)
- Subtraction (-)
- Multiplication (x)
- Division (÷)

### Additional Operations
- Percentage (%)
- Parentheses grouping ( ( ) )

## User Interface

Neat and user-friendly interface with a display area for input and results.

## Usage

1. **Numeric Input:** Press numeric buttons (0-9) to input numbers.
2. **Arithmetic Operations:** Use buttons for addition (+), subtraction (-), multiplication (x), and division (÷).
3. **Percentage:** Use the percentage button (%) to calculate percentages.
4. **Parentheses:** Utilize the parentheses button ( ( ) ) to group expressions.
5. **Clearing Input:**
    - Use the red 'x' button to clear one character at a time.
    - Use the 'C' button to clear the entire input.
6. **Equal Button:** Press the equal button (=) to evaluate the expression and display the result.

### Additional Notes

- The calculator automatically balances parentheses to ensure a valid expression.
- The code handles special characters such as "÷" and "x" for proper evaluation.
- Numeric input is formatted for better readability, including commas for thousands.

## Keyboard Shortcuts

- **Numeric Input:** Use the keyboard for numeric input (0-9).
- **Arithmetic Operations:**
    - Addition (+): Press the '+' key.
    - Subtraction (-): Press the '-' key.
    - Multiplication (x): Press the '*' key.
    - Division (÷): Press the '/' key.
- **Additional Operations:**
    - Percentage (%): Press the '%' key.
    - Parentheses ( ( ) ): Press the '(' key.
- **Clearing Input:**
    - Clear One Character: Press the 'Backspace' key.
    - Clear Entire Input: Press the 'Delete' key.
- **Equal Button:** Press the 'Enter' key to evaluate the expression.

## Dependencies

- Python 3.x
- PyQt6 library

## How to Run

1. Install PyQt6 using `pip install PyQt6`.
2. Run the application using `python calculator.py`.

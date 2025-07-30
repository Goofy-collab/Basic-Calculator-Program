# Basic-Calculator-Program
This Python program functions as a simple calculator that performs basic arithmetic operations

## Features

- Performs four basic arithmetic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
- Handles division by zero errors
- Validates user input for operations
- Displays formatted calculation results

## Installation

No installation required. Just ensure you have Python 3.6 or later installed.

To check your Python version:
```bash
python --version
```

## Usage

1. Run the script:
```bash
python index.py
```

2. Follow the prompts:
   - Enter the first number
   - Enter the second number
   - Choose an operation (+, -, *, /)

Example session:
```
Enter the first number: 10
Enter the second number: 5
Enter an operation (+, -, *, /): *
10 * 5 = 50
```

## How It Works

The program:
1. Takes two numbers as input
2. Asks for an arithmetic operation
3. Performs the calculation
4. Displays the result or an error message for:
   - Division by zero
   - Invalid operation input

## Code Structure

```python
# Get user input for numbers
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Get operation choice
operation = input("Enter an operation (+, -, *, /): ")

# Perform calculation based on operation
if operation == '+':
    # Addition logic
elif operation == '-':
    # Subtraction logic
# ... etc
```

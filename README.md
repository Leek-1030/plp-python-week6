
# Week 6 Assignment - Safe Functions

## Files

- safe_tools.py: Contains three safe functions using try and except to handle errors.

- README.md: Explains the assignment and the difference between bad input and unwise input.

## Question: Why can the if check not catch abc on its own?

An if check cannot catch "abc" when converting text into an integer because "abc" is not a valid whole number. Python raises a ValueError during the conversion, so we use try and except to handle the error and prevent the program from crashing.

# Stack Overflow Error in Recursive Function
This repository demonstrates a potential stack overflow error in a recursive Python function and how to resolve it using iteration.

## The Problem:
The `my_function` in `bug.py` uses recursion to calculate the sum of numbers from 1 to x.  However, for large values of x, this can lead to a `RecursionError` (stack overflow).
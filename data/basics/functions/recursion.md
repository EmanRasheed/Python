# Recursion

Function calling itself.

## Example
```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n-1)
Practice

Write a recursive function to sum first n numbers.

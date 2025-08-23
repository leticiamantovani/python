# Lesson 4: Return Statement

Functions are even more extensible then they seem. Instead of just printing a value, you can also return a value from a function. This allows you to use the result of a function in other parts of your code, outside of the original function.

Here's an example:

```python
def add_numbers(a, b):
    return a + b

result = add_numbers(5, 10)
print(result)  # This will print 15
```

In this example, the `add_numbers` function returns the sum of `a` and `b`. The returned value can then be stored in a variable (like `result`) and used later in the code.
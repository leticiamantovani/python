# Lesson 7: Scope

Consider the following code:

```python
n = 10
print(n)         # Output: 10

def print_number(n):
    print(n)

print_number(11) # Output: 11

print(n)         # Output: 10
```

1. First n is assigned the value of 10 and printed.

2. Next we call the function print_number and pass in the value 11. The name of the parameter for this function is also n. But this does not cause an error in Python.

3. After the function call is complete, the value of the original n is printed and it's still 10.
This can be explained by the concept of scope in programming.

In programming, the scope refers to the visibility or accessibility of variables within different parts of the code. **The value 11 passed into the print_number() function, is only accessible within the function. The function has its own scope, and the variable n inside the function is a different variable than the one outside the function.** This is why the value of the original n is still 10 after the function call.

## Why?

The value of the variable n outside the function remains unchanged because the variable n inside the function is a different variable, even though they share the same name. When we pass the value of n into the function, **the function creates a new copy of n that is local to the function (only accessible within the function).** Any changes made to this local variable do not affect the original variable outside the function.
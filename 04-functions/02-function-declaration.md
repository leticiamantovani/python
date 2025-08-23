# Lesson 2: Function Declaration

Similar to how variables must be declared before they can be used, **functions must also be defined before they can be called.**

```python
print(n) # error because n is not defined yet
n = 10 

print_number(5) # error because the function print_number is not defined yet

def print_number(n):
    print(n)


** Hoisting**
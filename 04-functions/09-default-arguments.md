# Lesson 9: Default Arguments

```python
def greet(name="world"):
    print("Hello, " + name + "!")

greet()       # This will print "Hello, world!"
greet("Bob")  # This will print "Hello, Bob!"
```

In the above code, we have given the parameter name a default value of "world". If we call the function without any arguments, the default value will be used. If we call the function with an argument, that argument will be used instead.

We can also have multiple parameters with default values. But the order of the parameters matters!**If you have a parameter with a default value, all parameters after it must also have default values.**

```python
# This is valid
def greet(greeting="Hello", name="world"):
    print(greeting + ", " + name + "!")

# This is valid
def greet(greeting, name="world"):
    print(greeting + ", " + name + "!")

# This is NOT valid
def greet(greeting="Hello", name):
    print(greeting + ", " + name + "!")
```
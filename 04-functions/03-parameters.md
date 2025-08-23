# Lesson 3: Parameters

You may have noticed that when we call the print() function, we put variables and strings inside of the parentheses. That's because a function can be defined with parameters.

```python
def greet(name):
    msg = "Hello, " + name
    print(msg)

greet("Alice")  # This will print "Hello, Alice"

```    
In the above code, we defined a function called greet that takes a parameter called name. We call the function by passing in "Alice" as the argument. Inside the function, we concatenate the string "Hello, " with the name parameter (we can combine strings with the + operator). We then print the result.

The power of parameters is that we can pass different values to the function and get different results. This allows us to reuse code without having to type it all out from scratch each time.

When calling a function, you can pass values, variables, or expressions as arguments to the function.

## What's the difference between arguments and parameters?

**Parameters** are the variables listed inside the parentheses in the function definition. They act as placeholders for the values that will be passed to the function when it is called.

**Arguments** are the actual values or variables that you pass to the function when you call it. They replace the parameters in the function definition.

For example, in the greet function:

```python
def greet(name):  # name is a parameter
    msg = "Hello, " + name
    print(msg)

greet("Alice")  # "Alice" is an argument
```

In this case, `name` is a parameter, and `"Alice"` is an argument. When we call `greet("Alice")`, the value `"Alice"` is passed to the function and replaces the parameter `name`.

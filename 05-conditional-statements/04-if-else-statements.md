# Lesson 4: If-Else Statement

It's common to want to run a separate piece of code when an if statement fails to execute. For example:

```python
balance = 100

if balance < 0:
    print("Account is overdrawn.")

if balance >= 0:
    print("Account is in good standing.")
```


The above code will print "Account is in good standing." because the balance is greater than or equal to 0. The first if statement will not execute because the condition is False. But we can rewrite this code using an else statement:

```python
balance = 100

if balance < 0:
    print("Account is overdrawn.")
else:
    print("Account is in good standing.")
```

This code is mostly equivalent to the first example. But the else block only executes if previous if statement fails to execute. We cannot have an else statement without an if statement preceding it.

Conditional statements like if and else can also be used to add multiple return statements within the same function as shown below.

```python
def get_max(a: int, b: int) -> int:
    if a > b:
        return a
    else:
        return b
```

The function above will return the maximum of two numbers. If a is greater than b, the function will return a. Otherwise, it will return b. Once a return statement is executed, the function will stop executing.
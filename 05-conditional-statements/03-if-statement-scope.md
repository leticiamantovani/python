# Lesson 3: If Statement Scope

Unlike functions, if statements do not create a new scope. **This means that variables defined inside an if statement are accessible outside of the if statement.** Here's an example:

```python
if True:
    message = "Hello"

print(message)  # This will print "Hello"
```

They can also update variables that were defined outside of the if statement. Here's an example:

```python
balance = -100

if balance < 0:
    balance = 0

print(balance)  # This will print 0
```

Within functions, if statements have the same scope as the function. This means that variables defined inside an if statement are accessible within that function, but not outside of it. Here's an example:

```python
def is_balance_low(balance: int):
    if balance <= 100:
        message = "Warning: Low balance."
    print(message)

is_balance_low(50)  # This will print "Warning: Low balance."
print(message)  # This will cause an error

```




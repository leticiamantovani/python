# Lesson 2: If Statement

What if we wanted to run some code only in certain situations? We can use the keyword if to do this, aka an if statement. Here's an example:

```python
account_balance = -100

if account_balance < 0:
    print("Your account is overdrawn.")

print("This is always printed.")
```

In this example, the code block under the if statement will only run if the account balance is less than 0. Notice how the code block is indented, just like with a function. This is how Python knows which code to run when the condition is true. **Code that is not indented, is not a part of the if statement, and will always run, regardless of the condition.**

If we had an if statement inside of a function, the code under the if statement would need to be indented twice, as shown below:

```python
def is_account_overdraw(balance: int):
    if account_balance < 0:
        print("Your account is overdrawn.")
```
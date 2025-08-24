# Lesson 5: Else If Statements

We can create a chain of conditional statements using the elif keyword (standing for else-if). This allows us to check multiple conditions in order, until one of them is true. Here's an example:

```python
balance = 1000

if balance < 0:
    print("Your account is overdrawn.")
elif balance == 0:
    print("Your account balance is zero.")
elif balance < 100:
    print("Your account balance is low.")
else:
    print("Your account balance is healthy.") # This will execute
```

Python will check each condition from top to bottom until one of them executes. In this case none of the first three conditions is True so the else block will execute.

- If the balance was -10, the if statement would execute, and the others would be skipped.
- If the balance was 0, the first elif statement would execute, and the others would be skipped.
- If the balance was 50, the second elif statement would execute, and the others would be skipped.

By the time we reach the else statement, we know the balance is not negative, zero, or less than 100, so it must be greater than or equal to 100.
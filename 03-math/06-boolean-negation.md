# Lesson 6: Boolean Negation

In Python, there is a keyword called not that is used to perform a logical negation operation.

Consider the following code:

```python
a = True
print(not a)  # Output: False
```

The output is False because the not operator inverts the value of a. If a is True, not a is False, and vice versa.

For all possible values of A, the truth table for the NOT operation is as follows:

| A     | not A |
|-------|-------|
| True  | False |
| False | True  |

**To summarize, the NOT operation returns True if the operand is False, and False if the operand is True.** This holds even if we have more than one operand:

```python
a = True
b = False
print(not a and not b)  # Output: False
``` 

OR

```python
a, b = True, False
print(not (a and b))  # Output: True
```
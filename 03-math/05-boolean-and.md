# Lesson 5: Boolean and

In Python there is also a keyword called and that is used to perform a logical AND operation.

Consider the following code:

```python
a = True
b = False
print(a and b)  # Output: False
```

The output is False because both operands are not True. Suppose we have two people, Alice and Bob. If Alice "Likes ice cream" and Bob "Does not like ice cream", then the statement "Alice and Bob like ice cream" is false because both of them do not like ice cream.

For all possible pairs of values of A and B, the truth table for the AND operation is as follows:

| A     | B     | A and B |
|-------|-------|---------|
| True  | True  | True    |
| True  | False | False   |
| False | True  | False   |
| False | False | False   |

**To summarize, the AND operation returns True if both of the operands is True.** This also holds if we have more than two operands:

```python
a, b, c = True, True, True
print(a and b and c)  # Output: True
```
# Lesson 4: Boolean OR

Boolean algebra is a branch of mathematics that deals with logical values and operations. We will be focusing on the parts of Boolean Algebra that are most important in programming.

In Python there is a keyword called or that is used to perform a logical OR operation.

Consider the following code:

```python
a = True
b = False
print(a or b)  # Output: True
```

The output is True because at least one of the operands is True. It's not that different from human language. Suppose we have two people, Alice and Bob. If Alice "Likes ice cream" and Bob "Does not like ice cream", then the statement "Alice or Bob likes ice cream" is true because at least one of them likes ice cream. If both like ice cream, the statement is still true (maybe in english it would be better to say "Alice and/or Bob like ice cream").

For all possible pairs of values of A and B, the truth table for the OR operation is as follows:

| A     | B     | A or B |
|-------|-------|--------|
| True  | True  | True   |
| True  | False | True   |
| False | True  | True   |
| False | False | False  |

**To summarize, the OR operation returns True if at least one of the operands is True**. This holds even if we have more than two operands:

```python
a, b, c = False, False, True
print(a or b or c)  # Output: True
```
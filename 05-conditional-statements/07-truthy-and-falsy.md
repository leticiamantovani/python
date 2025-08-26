# Lesson 7: Truthy and Falsy

In Python it's possible to use non-boolean values to execute conditional statements.

```python
msg = ""
if msg:
    print("Message is not empty.") # This will not be printed

msg = "Hello, World!"
if msg:
    print("Message is not empty.") # This will be printed
```

This is because Python has the concept of truthy and falsy values. A value is considered truthy if it evaluates to True in a boolean context. A value is considered falsy if it evaluates to False in a boolean context. The condition in an if statement is considered a boolean context.

A value is falsy if it is:

- False (boolean)
- None (NoneType)
- 0 (integer)
- 0.0 (float)
- "" (empty string)
- [] (empty list)
- Most other empty collections (e.g. empty tuple, empty set, empty dictionary)

A value is truthy if it is:

- True (boolean)
- All integers other than 0
- All floats other than 0.0
- All strings other than ""
- All collections with at least one element
This means that the following two if statements are equivalent:

```python
x = 10

if x:
    print("x is not zero")

if x != 0:
    print("x is not zero")

```

As a beginner, it may be fine for you to prefer the second form, as it is more explicit. But be aware that the first form is more idiomatic in Python (more common and the intended way to use Python).
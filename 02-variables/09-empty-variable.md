# Lesson 9: Empty Variable

If we want to declare a variable without a value, we can use the None keyword. This is used to indicate that the variable has no value.

If we try to declare a variable without explicity assigning a value to it, we will get an error.

```python
var
```

However, if we assign the variable to None, we can declare the variable without a value.

```python
var = None
```

## What's the difference between null and None?

In Python, `None` is a special constant that represents the absence of a value or a null value. It is similar to `null` in other programming languages like JavaScript or Java. However, `None` is its own data type (NoneType) in Python.

```python
var = None
print(var)  # Output: None
```

## Is there a null value in Python?
No, Python does not have a built-in null value. The closest equivalent is `None`, which is used to indicate the absence of a value.
## Lesson 7: Type Casting

**Type casting is the process of converting a variable from one type to another**. In Python, you can explicitly change the type of a variable using built-in functions like `int()`, `float()`, and `str()`.

### Examples:

1. **Converting a float to an integer**:
```python
x = 5.7
y = int(x)  # y will be 5
```

2. **Converting an integer to a float**:
```python
x = 5
y = float(x)  # y will be 5.0
```

3. **Converting a number to a string**:
```python
x = 5
y = str(x)  # y will be "5"
```

## Is there a way to convert a string to a number?

Yes, you can convert a string to a number using the `int()` or `float()` functions, depending on whether you want an integer or a float.

```python
x = "5"
y = int(x)  # y will be 5
```

## What about string letters?

If you have a string that represents a letter and you want to convert it to its corresponding ASCII value, you can use the `ord()` function. Conversely, to convert an ASCII value back to a character, you can use the `chr()` function.

```python
x = "A"
y = ord(x)  # y will be 65
```

```python
x = 65
y = chr(x)  # y will be "A"
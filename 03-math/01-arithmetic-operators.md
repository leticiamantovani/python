## Lesson 1: Arithmetic Operators

In Python, arithmetic operators are used to perform mathematical operations. The most common arithmetic operators are:

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Modulus (`%`)

### Example

```python
a = 10
b = 5

# Addition
c = a + b
print(c)  # Output: 15

# Subtraction
c = a - b
print(c)  # Output: 5

# Multiplication
c = a * b
print(c)  # Output: 50

# Division
c = a / b
print(c)  # Output: 2.0 # HERE IS ALWAYS FLOAT

# Modulus
c = a % b
print(c)  # Output: 0
```

If we divide y by x, the result will be 2.0 and not 2. This is because **the result of division is always a float in Python.**

For the other arithmetic operators, the result will be an integer if both operands are integers. If one of the operands is a float, the result will be a float.

## What about the order of operations?

I'm glad you asked! The order of operations in Python is the same as in mathematics. The acronym PEMDAS can help you remember the order:

1. Parentheses
2. Exponents
3. Multiplication and Division (from left to right)
4. Addition and Subtraction (from left to right)

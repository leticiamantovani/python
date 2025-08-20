# Lesson 6: Dynamic Typing

**In Python a single variable's type can change throughout the code. This is called dynamic typing**. For example, the following code will run without any errors:

```python
variable = 10         # int type
variable = "Hello"    # str type
variable = [1, 2, 3]  # list type
```

Not all languages support dynamic typing. In some languages, a variable's type must be explicitly declared and cannot be changed. This is called static typing. For example, in Java, the following code will cause an error:

```java
int variable = 10;
variable = "Hello";  // Error: incompatible types
```
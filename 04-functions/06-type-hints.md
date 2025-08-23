# Lesson 5: Type Hints


In Python, you can add type hints to your functions to indicate what type of data the function expects to receive and return. **This is not required, but it can be helpful for other developers who are reading your code.**

Here's an example:

```python
def add_numbers(a: int, b: int) -> int:
    return a + b
```

In this example, the type hints indicate that the `add_numbers` function expects two integer arguments (`a` and `b`) and will return an integer.

Type hints can make your code more readable and easier to understand, especially in larger codebases.

To **add a type hint for a parameter, you add a colon after the parameter name and then the type of data you expect. To add a return type, you add a right arrow (->) after the closing parenthesis and then the type of data you expect to return (before the colon).**

**Type hints don't change how the function works, for example, we could still pass a COUPLE OF STRINGS** to the add function above and it would still work.

What if we had a function that did not return anything? The return type would be None.

```python
def greet(name: str) -> None:
    print("Hello, " + name)
```

In this example, the `greet` function takes a string argument (`name`) and does not return a value. The return type is indicated as `None`.

Hello, NeetCode
<
class
'NoneType'
>


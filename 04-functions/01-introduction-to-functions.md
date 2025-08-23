# Lesson 1: Introduction to Functions

We learned that variables can store values that can be reused later in the program. **Functions are even more powerful because they can store entire blocks of code that can be reused multiple times.**

Below we are defining a function.

```python
def greet():
    print("Hello, world!")
```

**Functions are defined using the def keyword followed by the function name and parentheses with a colon ():.** The code that belongs to the function must be indented with whitespace. In this case we have just a single line of code that prints "Hello, world!". Functions can have multiple lines of code too, but they can not be empty.

After defining a function, you can use it by typing the name of it followed by parentheses (). This is called calling the function.

greet()  # This will print "Hello, world!"
This is not so different than how we use built-in functions like print(). We just need to define our own functions before we can use them.

## Indentation Importance

How much should we indent code within a function?

**In Python, indentation is used to define code blocks.** All code that belongs to a function should be indented. **The standard convention is to use 4 spaces for indentation,** which is what we are following in this course. Sometimes code is only indented by 2 spaces, but this is less common. Either way, it's important to be consistent with your indentation. This is the only way Python knows what code belongs to a function.




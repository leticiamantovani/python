# Lesson 8: Global vs Local Scope

Here are a few more examples illustrating scope in Python:

```python

def declare_variable() -> None:
    inside_function_only = 10
    return

declare_variable()
print(inside_function_only) # This will raise a NameError
```

In the code above, the variable inside_function_only is declared inside the function declare_variable. This variable has a local scope and is only accessible within the function. Attempting to access it outside the function will result in a NameError.

```python
n = 10

def print_global_variable() -> None:
    print(n)

print_global_variable() # This will print 10
```

In the code above, the variable n is declared outside the function print_global_variable. This variable has a global scope, since it's not within a function, and can be accessed from anywhere in the program, including inside functions.

Note: We saw earlier, that if the function has a parameter with the same name as a global variable, the function will use the local variable instead of the global variable.

 - **Global Scope**:

    - Variables declared outside of any function have a global scope.
    - They can be accessed from anywhere in the program, including inside functions.

 - **Local Scope**:

    - **Variables declared within a function have a local scope.**
    - They can only be accessed within the function in which they are defined.
    - Local variables are created when the function is called and destroyed when the function exits.


SUMMARY:

In Python, variables have a scope that determines where they can be accessed. There are two main types of scope: global and local.

- **Global Scope**: Variables declared outside of any function have a global scope and can be accessed from anywhere in the program.
- **Local Scope**: Variables declared within a function have a local scope and can only be accessed within that function. Local variables are created when the function is called and destroyed when the function exits.
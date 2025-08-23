# Lesson 4: Multiple Parameters

**Functions can be defined to accept more than one parameter. The parameters are separated by commas in the function definition.** When calling the function, the arguments are also separated by commas.

```python
def greet(name, greeting):
    message = greeting + " " + name
    print(message)

greet("Alice", "Hello")  # This will print "Hello Alice"
```

Notice how we concatenate three strings together (greeting, " ", and name) using the + operator. This allows us to combine the strings into one message.

Challenge
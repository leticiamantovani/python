## Lesson 8: Type Errors

Even though variable types can change, there are still rules about what types of variables can be used together. For example, the following code will cause an error:

```python
message = "Hello"
message = int(message)
```


We can't convert a string to an integer, unless the string is a number. This code will cause a **ValueError.**
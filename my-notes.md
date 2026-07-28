Everything we create in python is an object. (str, list, tuple, dict, func etc....)

When Python was created, its developers already wrote classes for common data types like: int, float, str, list, tuple, dict, set, bool. These are called built-in classes.

what happens when we write a string? Suppose we write:

```python
name = "Ranjan"
```

It looks like you are simply creating a string. But internally, Python does something similar to this:

```python
name = str("Ranjan")
```

The str class creates a string object. So:
str → class
"Ranjan" → object of the str class

```python
print(type(name))

Output: <class 'str'>
```

This means: name is an object created from the str class.

other examples


```python
age = 22
numbers = [10, 20, 30]
student = {
    "name": "Ranjan",
    "roll_no": 7
}
```
Internally, Python is roughly doing something like:
```python
age = int(22)
numbers = list([10, 20, 30])
student = dict({
    "name": "Ranjan",
    "age": 22
})
```

numbers is an object of the list class.
dict is the class. student is an object of the dict class.
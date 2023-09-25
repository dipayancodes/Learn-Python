# Learn Python from DipayanCodes

Welcome to the ultimate Python programming tutorial! In this tutorial, you will learn Python from the very basics to becoming a Python master.

## Table of Contents
1. [Introduction to Python](#introduction-to-python)
2. [Variables and Data Types](#variables-and-data-types)
3. [Control Structures](#control-structures)
4. [Functions](#functions)
5. [Data Structures](#data-structures)
6. [Object-Oriented Programming](#object-oriented-programming)
7. [File Handling](#file-handling)
8. [Error Handling](#error-handling)
9. [Modules and Packages](#modules-and-packages)
10. [Advanced Topics](#advanced-topics)
11. [Conclusion](#conclusion)

## 1. Introduction to Python
Python is a versatile, high-level programming language known for its simplicity and readability. It's an excellent language for beginners and professionals alike.

### Installing Python
You can download and install Python from the [official website](https://www.python.org/downloads/). Make sure to choose the appropriate version for your operating system.

### Hello, World!
Let's start with the traditional "Hello, World!" program:

```python
print("Hello, World!")
```

## 2. Variables and Data Types
In Python, variables are used to store data. Python has various data types, including integers, floats, strings, lists, and dictionaries.

```python
# Variables and data types
my_integer = 42
my_float = 3.14
my_string = "Hello, Python!"
my_list = [1, 2, 3, 4, 5]
my_dict = {"name": "John", "age": 30}
```

## 3. Control Structures
Control structures help you manage the flow of your Python programs. We'll cover if statements, loops, and more.

```python
# Conditional statements
if condition:
    # code to execute if condition is True
else:
    # code to execute if condition is False

# Loops
for item in iterable:
    # code to execute for each item

while condition:
    # code to execute while condition is True
```

## 4. Functions
Functions are reusable blocks of code. You can define your own functions in Python.

```python
# Function definition
def greet(name):
    return f"Hello, {name}!"

# Function call
result = greet("Alice")
print(result)
```

## 5. Data Structures
Python offers various data structures like lists, tuples, sets, and dictionaries to store and manipulate data efficiently.
```python
# Lists
my_list = [1, 2, 3, 4, 5]
print(my_list[0])  # Accessing an element

# Tuples
my_tuple = (1, 2, 3)
print(my_tuple[1])

# Sets
my_set = {1, 2, 2, 3}
print(my_set)  # Removes duplicates

# Dictionaries
my_dict = {"name": "John", "age": 30}
print(my_dict["name"])  # Accessing a value by key
```

## 6. Object-Oriented Programming
Python supports object-oriented programming (OOP). You'll learn about classes, objects, and inheritance.

```python
# Class definition
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        return f"Hello, my name is {self.name} and I'm {self.age} years old."

# Creating an object
person1 = Person("Alice", 25)
print(person1.greet())
```

## 7. File Handling
Python can read and write files. We'll cover file I/O operations.

```python
# Writing to a file
with open("example.txt", "w") as file:
    file.write("Hello, File!")

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

## 8. Error Handling
Learn how to handle exceptions and errors gracefully in Python.

```python
try:
    result = 10 / 0  # Division by zero
except ZeroDivisionError:
    print("Error: Division by zero!")
```

## 9. Modules and Packages
Python has a rich ecosystem of modules and packages. You'll discover how to use them effectively.

```python
# Importing a module
import math
print(math.sqrt(16))  # Square root function from the math module

# Creating and using a package (folder with __init__.py file)
# See: https://docs.python.org/3/tutorial/modules.html#packages
```

## 10. Advanced Topics
Explore advanced Python topics like decorators, generators, and more.

```python
# Decorator example
def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

@my_decorator
def say_hello():
    print("Hello!")

say_hello()

# Generator example
def countdown(n):
    while n > 0:
        yield n
        n -= 1

for i in countdown(5):
    print(i)
```


## 11. Conclusion
Congratulations! You've completed this Python tutorial and are well on your way to becoming a Python master. Keep practicing, and you'll continue to improve your Python skills.

Happy coding!

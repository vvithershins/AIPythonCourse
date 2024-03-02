# Day 2: Variables and Printing

Part 1: Introduction and Lesson
Introduction:
Welcome to Day 2 of our Python journey! Today, we'll dive deeper into the world of variables. Variables are used to store and manipulate data in Python. We'll focus on two common types of variables: strings (text) and numbers (integers and floats).

Lesson:
Variables in Python can hold different types of data. Let's start by declaring some variables and printing their values:

```python
# String variable
name = "Alice"
print("Name:", name)

# Integer variable
age = 25
print("Age:", age)

# Float variable
height = 5.8
print("Height:", height)
```

Explanation:

String Variable (name):

We declare a variable name and assign it the value "Alice".
The print() function is used to display the value of the name variable. We include a label "Name:" to provide context.
Integer Variable (age):

We declare a variable age and assign it the value 25.
The print() function is used to display the value of the age variable. We include a label "Age:" to provide context.
Float Variable (height):

We declare a variable height and assign it the value 5.8.
The print() function is used to display the value of the height variable. We include a label "Height:" to provide context.
These examples demonstrate how to declare variables and print their values using the print() function. We have variables representing a person's name, age, and height, each assigned a different data type (string, integer, and float, respectively).

Common Errors:
Forgetting to enclose strings in quotes will result in a syntax error.
```python
# Syntax error: String not enclosed in quotes
message = Hello, World!
```

Using variable names that start with a number or contain special characters other than underscores will result in a syntax error.
```python
# Syntax error: Variable name starts with a number
2nd_number = 10

# Syntax error: Variable name contains special character
user@name = "Alice"
```
Attempting to perform operations between incompatible data types (e.g., adding a string and a number) will result in a TypeError.
```python
# TypeError: Attempting to add a string and a number
result = "Hello" + 5
```
More Technical Information:
Python is dynamically typed, meaning you don't need to specify the data type of a variable explicitly.
```python
x = 10  # x is an integer
x = "Hello"  # x is now a string
print(type(x)) # to check what type x is
```
Variables can be reassigned to different values of different types without any issues due to dynamic typing.

Understanding these common errors and technical details will help you write cleaner and more efficient code. If you have any questions or need further clarification, feel free to ask!

Challenge:
Your challenge is to declare variables for your own name, age, and height, and then print their values using the print() function.


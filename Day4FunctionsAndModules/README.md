Day 4: Functions and Modules
Introduction
In Day 4, we'll explore the concept of functions and modules in Python. Functions allow us to encapsulate reusable blocks of code, while modules enable us to organize our code into separate files for better maintainability and reusability.

What We'll Cover
Creating and using functions
Function parameters and return values
Introduction to modules and importing modules
Lesson
Functions
A function in Python is a block of code that performs a specific task. Functions help us avoid repetitive code and make our code more modular and easier to understand.

Here's how you define and use a function in Python:

```python
Copy code
# Define a function
def greet(name):
    """Greets the user by name."""
    print("Hello, " + name + "!")

# Call the function
greet("Alice")
greet("Bob")
```
In this example:

We define a function called greet() that takes one parameter (name) and prints a greeting message.
We call the greet() function twice, passing different names as arguments.
Function Parameters and Return Values
Functions can also accept parameters and return values. Parameters allow us to pass data into a function, and return values allow the function to send data back to the caller.

```python
Copy code
# Function with parameters and return value
def add(x, y):
    """Adds two numbers and returns the result."""
    return x + y

# Call the function and store the result
result = add(3, 5)
print("The sum is:", result)
```
In this example:

We define a function called add() that takes two parameters (x and y) and returns their sum.
We call the add() function with arguments 3 and 5, and store the result in a variable named result.
Common Errors
One common error when defining functions is forgetting to use the def keyword or incorrectly indenting the function body.

```python
Copy code
# Incorrect function definition
greet(name):
    print("Hello, " + name + "!")
```
Challenge
Your challenge for today is to create a simple program that defines a function to calculate the area of a rectangle. The function should accept the width and height of the rectangle as parameters and return the area.

Here's a suggested outline:

Define a function called calculate_area() that takes two parameters: width and height.
Calculate the area of the rectangle using the formula: area = width * height.
Return the calculated area from the function.
Call the function with different values for width and height and print the result.
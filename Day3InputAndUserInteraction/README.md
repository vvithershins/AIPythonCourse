Day 3: Input and User Interaction
Introduction
In Day 3, we'll delve into accepting user input and interacting with the user through the input() function. This will allow us to create programs that can respond dynamically to user actions and inputs.

What We'll Cover
Introduction to the input() function
Accepting user input
Printing user input back to the user
Lesson
The input() function is used in Python to accept user input from the keyboard. It prompts the user to enter a value, which can be stored in a variable for further processing.

Here's a basic example of how to use the input() function:

```python
Copy code
# Accept user input
name = input("Enter your name: ")

# Print the input back to the user
print("Hello,", name, "! Nice to meet you.")
```
In this example:

The input("Enter your name: ") statement prompts the user to enter their name. Whatever the user types in response will be stored in the name variable.
The print("Hello,", name, "! Nice to meet you.") statement then prints a greeting message to the user, including the name they entered.
Common Errors
One common error when using the input() function is forgetting to convert the input to the appropriate data type. By default, input() returns a string, so if you're expecting a numeric input, you'll need to convert it using functions like int() or float().

```python
Copy code
# Accepting a number as input
age = int(input("Enter your age: "))
```
Challenge
Your challenge for today is to create a simple program that asks the user for their name and age, then prints out a message including both pieces of information.

Here's a suggested outline:

Prompt the user to enter their name using the input() function.
Prompt the user to enter their age using the input() function.
Print a message that includes both the name and age entered by the user.
Feel free to experiment and add more functionality to your program if you'd like!
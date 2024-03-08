Day 5: Lists and Tuples
Introduction
Today, we'll delve into two essential data structures in Python: lists and tuples. Lists are mutable sequences of elements, while tuples are immutable sequences. Understanding how to work with these data structures is crucial for managing collections of items in Python effectively.

What We'll Cover
Creating and modifying lists
Accessing elements in lists
List methods for manipulation
Creating and using tuples
Differences between lists and tuples
Lesson
Lists
A list in Python is a mutable, ordered collection of items. Lists are created using square brackets [] and can contain elements of different data types.

Here's how you create and work with lists in Python:

```python
Copy code
# Creating a list
numbers = [1, 2, 3, 4, 5]
fruits = ["apple", "banana", "cherry"]

# Accessing elements in a list
print(numbers[0])  # Output: 1
print(fruits[1])   # Output: banana

# Modifying a list
fruits.append("orange")   # Add an element to the end of the list
fruits.remove("banana")   # Remove a specific element from the list
```
Tuples
A tuple in Python is an immutable, ordered collection of items. Tuples are similar to lists, but they cannot be modified after creation.

Here's how you create and work with tuples in Python:

```python
Copy code
# Creating a tuple
point = (10, 20)

# Accessing elements in a tuple
print(point[0])  # Output: 10
```
Common Errors
One common error when working with lists is trying to access an index that doesn't exist. This results in an "IndexError."

```python
Copy code
numbers = [1, 2, 3]
print(numbers[3])  # IndexError: list index out of range
```

Challenge
Your challenge for today is to create a program that demonstrates your understanding of lists and tuples. Here are some suggested tasks:

Create a list of your favorite movies and print them out.
Create a tuple containing the coordinates of a point and print them out.
Experiment with different list methods, such as append(), remove(), insert(), etc.
Try accessing elements in a list and tuple using negative indexing.
Feel free to explore and experiment with lists and tuples further!


Negative indexing allows you to access elements from the end of a list or tuple by using negative numbers as indices. For example, -1 refers to the last element, -2 refers to the second last element, and so on.

Here's an example:

```python
numbers = [10, 20, 30, 40, 50]

# Accessing elements using negative indexing
print(numbers[-1])  # Output: 50 (last element)
print(numbers[-2])  # Output: 40 (second last element)
```

Similarly, you can use negative indexing with tuples as well. Experimenting with negative indexing will help reinforce your understanding of how it works.
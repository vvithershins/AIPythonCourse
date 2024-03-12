# More Errors

1 Key Error: This error occurs when you try to access a key in a dictionary that does not exist.

```python
shoppingList = {"chicken": 1, "breadloaves": 2, "gallons of milk": 2}
print(shoppingList["eggs"])  # Key Error: 'eggs' not in dictionary
```

2 Type Error: This error may occur when trying to perform unsupported operations on dictionaries or sets.

```python
shoppingList = {"chicken": 1, "breadloaves": 2, "gallons of milk": 2}
print(shoppingList["chicken"] + " eggs")  # Type Error: unsupported operand type(s) for +: 'int' and 'str'
```
Additional Information:

Mutable vs. Immutable: Dictionaries are mutable data types in Python, meaning they can be modified after creation. Sets are also mutable. However, keys in a dictionary must be immutable, while values can be mutable or immutable.

Hashable Objects: In Python, dictionary keys must be hashable objects. Immutable types like strings, integers, and tuples are hashable, while mutable types like lists and dictionaries are not.

Set Operations: Sets support various set operations such as union, intersection, difference, and symmetric difference, which can be useful for performing set calculations.
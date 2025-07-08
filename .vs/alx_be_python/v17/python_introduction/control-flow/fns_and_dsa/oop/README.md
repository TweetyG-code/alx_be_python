# Book Class - Python OOP Practice

This project demonstrates the use of **Python magic methods** by implementing a simple `Book` class.

## 📚 Objective

Master Python's magic (dunder) methods by creating a `Book` class that uses:
- `__init__`: Constructor
- `__del__`: Destructor
- `__str__`: User-friendly string representation
- `__repr__`: Official string representation

## 🧠 Concepts Practiced

- Object-Oriented Programming (OOP)
- Magic methods in Python
- Clean code organization
- Class design and object lifecycle

## 📄 Files

| File         | Description |
|--------------|-------------|
| `book_class.py` | Contains the `Book` class definition. |
| `main.py`        | Script for testing the `Book` class. |

## 📦 Book Class Details

### Attributes:
- `title` (str): Title of the book.
- `author` (str): Author's name.
- `year` (int): Year of publication.

### Magic Methods:

| Method        | Purpose |
|---------------|---------|
| `__init__`    | Initializes the book object. |
| `__del__`     | Prints `"Deleting <title>"` when the object is deleted. |
| `__str__`     | Returns a user-friendly description. Format: `"<title> by <author>, published in <year>"`. |
| `__repr__`    | Returns a string that can recreate the object. Format: `Book('<title>', '<author>', <year>)`. |

## 🧪 Sample Output (from `main.py`)

```text
1984 by George Orwell, published in 1949
Book('1984', 'George Orwell', 1949)
Deleting 1984

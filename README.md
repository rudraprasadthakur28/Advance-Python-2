# Advanced Python 2

This repository contains my Advanced Python 2 practice focused on virtual environments, package management, string methods, and functional programming concepts.

## Topics Covered

- Virtual Environment (`venv`)
- `pip`
- `pip freeze`
- Lambda Functions
- `join()` Method
- `format()` Method
- `map()`
- `filter()`
- `reduce()`

## Virtual Environment

A virtual environment creates an isolated Python environment for a project.

It helps keep project dependencies separate from other Python projects.

Example:

```bash
python -m venv myenv
```

## pip

`pip` is Python's package manager. It is used to install and manage Python packages.

Example:

```bash
pip install package_name
```

## pip freeze

`pip freeze` displays the installed Python packages and their versions.

Example:

```bash
pip freeze
```

It can also be used to create a requirements file:

```bash
pip freeze > requirements.txt
```

## Lambda Functions

A lambda function is a small anonymous function that can be written in a single expression.

Example:

```python
square = lambda x: x * x
```

## `join()` Method

The `join()` method is used to join elements of an iterable into a single string.

Example:

```python
words = ["Python", "is", "easy"]
result = " ".join(words)
```

## `format()` Method

The `format()` method is used to insert values into a string.

Example:

```python
name = "Harry"
print("Hello, {}".format(name))
```

## `map()`

`map()` applies a function to each item of an iterable.

Example:

```python
numbers = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, numbers))
```

## `filter()`

`filter()` is used to select elements from an iterable based on a condition.

Example:

```python
numbers = [1, 2, 3, 4, 5]
result = list(filter(lambda x: x % 2 == 0, numbers))
```

## `reduce()`

`reduce()` repeatedly applies a function to the elements of an iterable and reduces them to a single value.

Example:

```python
from functools import reduce

numbers = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, numbers)
```

## Learning Goal

The goal of this repository is to understand Python virtual environments, package management, and functional programming tools such as lambda functions, `map()`, `filter()`, and `reduce()`.

## Status

Completed as part of my Advanced Python learning journey.
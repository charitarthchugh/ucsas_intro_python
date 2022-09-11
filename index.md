---
marp: true
title: Test MARP
theme: gradient
class: [blue]
---

<!-- _class: lead -->

![bg right](assets/python-logo-colourful.png)

# Introduction to Python

## UCSAS 2022

### Charitarth Chugh

---

# About Me

![bg right 60%](https://raw.githubusercontent.com/charitarthchugh/website/master/assets/images/myself.png)

- Second Year Computer Scince Student at UConn

## Interests

- Deep Learning
- Linux
- Software Development

## Aspirations:

Build really cool stuff related to deep learning!

---

# Why Python?

- Python is a language with very diverse applications, from software development to research
- The ecosystem of libraries and tools is awesome, which makes finding niche packages a breeze.
  - If you are not able to find anything that suits your needs, it is fairly easy to create a python package of your own as well.
---
# Prerequisites:

A device with Internet access

### Getting set up:

In the terminal, run
`pip install -U numpy pandas matplotib seaborn`

---

<!-- _class: [blue,tinytext] -->

# What we will be covering today!

- Python Syntax (Variables, Indentation, Comments)
- Data Types and Methods
  - Strings (`str`)
  - Numerical types (`int`, `float`, `complex`)
  - Mapping (`dict`)
  - Sets (`sets`, `frozenset`)
- Conditions, Loops and Functions
- Basic modules and their respective functions
  - `numpy`: Arrays, Universal Functions (Vectorized), Random numbers (Simulations)
  - `pandas`: DataFrames, Data Manipulation
  - Miscellaneous

---

# Syntax

- To comment a line, prefix it with a `#`
- In Python, a new line indicates a start of a new command

```python
# Print Hello, UCSAS
print("Hello, UCSAS!")

print("Workshop going good?")

```

---

## Numerical and Boolean Data Types

- Integer (`int`)
- Float (`float`)
- complex (`complex`)
- Boolean (`bool`)
  - Difference here is true is `True` and false is `False`

---

# Data

## Strings

- Multiline Strings

---

# Data Types

- Obviously this is not an exhaustive list
- So if you ever need to inspect the type of something, there is a nice built-in `type()` that finds the type.

---

# Variable Assignment

- Is as simple as writing the name of the variable `=` to some value.
- There is no need to define the type of the variable in Python, as it is determined on its own.

```python
# Integer Assignment
x = 2
# String
z = "UCSAS"
## Boolean
w = True
print(x)
print(z)
print(w)
```

---

# Sidenote: Getting help in Python

For any object, you can call the `dir()` function to see all the methods that it supports.
Example:

```python
>>> dir(list)
['__add__', '__class__', '__class_getitem__', ...]
```

For any function, you can call the `help()` function to read more about what the function does and what its arguments represent

```python
>>> help(sorted)
sorted(iterable, /, *, key=None, reverse=False)
    Return a new list containing all items from the iterable in ascending order.

    A custom key function can be supplied to customize the sort order, and the
    reverse flag can be set to request the result in descending order.
```

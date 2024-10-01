# 📦 Python Modules and Packages

This repository provides a hands-on guide to using Python modules and packages, making your code more modular and organized.

## 📝 What Are Modules?

A **module** is simply a file containing Python code. You can define functions, classes, and variables within a module and then import them into other Python scripts. This helps you organize your code into logical sections.

### How to Use a Module

1. **Create a Module:**
   - Write your code in a `.py` file. For example, create `mymodule.py`:
     ```python
     # mymodule.py
     def greet(name):
         return f"Hello, {name}!"
     ```

2. **Import and Use the Module:**
   - In another script, import the module and call its functions:
     ```python
     from mymodule import greet
     
     print(greet("World"))  # Output: Hello, World!
     ```

## 📂 What Are Packages?

A **package** is a directory that contains multiple related modules. It allows you to group similar modules together. A package must include an `__init__.py` file (which can be empty), marking the directory as a package.

### How to Use a Package

1. **Create a Package:**
   - Structure your project directory as follows:
     ```
     mypackage/
     ├── __init__.py
     ├── module1.py
     └── module2.py
     ```

2. **Define Modules within the Package:**
   - Inside `module1.py`:
     ```python
     # module1.py
     def add(a, b):
         return a + b
     ```

   - Inside `module2.py`:
     ```python
     # module2.py
     def subtract(a, b):
         return a - b
     ```

3. **Import and Use the Package:**
   - In your script, import the modules from the package:
     ```python
     from mypackage.module1 import add
     from mypackage.module2 import subtract
     
     print(add(5, 3))       # Output: 8
     print(subtract(5, 3))  # Output: 2
     ```

## 🚀 Getting Started

To start using modules and packages, clone this repository and explore the examples provided. Each example is self-contained, demonstrating how to create and import modules and packages in your Python projects.

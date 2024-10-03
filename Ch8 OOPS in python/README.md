Object-Oriented Programming (OOP) in Python 🐍
📚 Overview
This repository provides a collection of Python examples that illustrate key Object-Oriented Programming (OOP) concepts. Dive into how to use classes, objects, inheritance, encapsulation, and polymorphism to write clean, modular, and maintainable code.

🔍 Concepts Covered
1. Classes and Objects 📦
Classes: Blueprints for creating objects. Define attributes and methods.
Objects: Instances of classes with specific values and behaviors.
Example: class Person: defines a person with attributes like name and age and methods like greet().

2. Inheritance 🧬
Inheritance: Mechanism to create a new class based on an existing class, inheriting attributes and methods.
Example: class Student(Person): extends the Person class to include student-specific attributes and methods.

3. Encapsulation 🔒
Encapsulation: Hides the internal state of an object and only exposes a controlled interface. Uses private and protected attributes.
Example: Using self.__private_var to restrict access to internal attributes.

4. Polymorphism 🧩
Polymorphism: Allows methods to do different things based on the object’s class. Implemented through method overriding.
Example: class Animal: with a method make_sound(), and class Dog(Animal): overriding make_sound() to bark.


5. Magic Methods ✨
Magic methods, also known as dunder methods (double underscore methods), allow you to define the behavior of objects for built-in operations.

Common Magic Methods:

__init__: Initializes a new instance of a class.

__str__: Returns a string representation of an object.

__repr__: Returns an official string representation of an object.

__len__: Returns the length of an object.

__getitem__: Gets an item from a container.

__setitem__: Sets an item in a container.


6. Operator Overloading 🔄
Operator overloading allows you to define the behavior of operators (+, -, *, etc.) for custom objects.


Common Operator Overloading Magic Methods:

__add__(self, other): Adds two objects using the + operator.

__sub__(self, other): Subtracts two objects using the - operator.

__mul__(self, other): Multiplies two objects using the * operator.

__truediv__(self, other): Divides two objects using the / operator.

__eq__(self, other): Checks if two objects are equal using the == operator.


7. Custom Exceptions 🚨
You can create your own exceptions by defining a new exception class that inherits from the built-in Exception class.

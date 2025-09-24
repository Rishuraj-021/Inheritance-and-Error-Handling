# Inheritance
## Aim:

To study and implement the concept of Inheritance in C++ and understand how one class can acquire the properties and functionalities of another class to promote code reusability and extensibility.

## Theory:

Inheritance is one of the core features of Object-Oriented Programming (OOP) in C++. It allows a new class (called the derived class) to acquire the properties (data members) and behaviors (member functions) of an existing class (called the base class).

This promotes code reusability, extensibility, and establishes a hierarchical relationship between classes.

Key Concepts

Base Class (Parent/Superclass): The class whose features are inherited.

Derived Class (Child/Subclass): The class that inherits the features of the base class.

Access Specifiers in Inheritance:

Public Inheritance: Public members → remain public, Protected → remain protected, Private not inherited.

Protected Inheritance: Public & Protected of base → become protected in derived.

Private Inheritance: Public & Protected of base → become private in derived.

### Types of Inheritance:

Single Inheritance – One base class, one derived class.

Multiple Inheritance – One derived class inherits from multiple base classes.

Multilevel Inheritance – A derived class becomes a base class for another class.

Hierarchical Inheritance – Multiple derived classes inherit from one base class.

Hybrid Inheritance – Combination of two or more types of inheritance.

### Advantages of Inheritance:

Promotes code reusability by using existing code in new classes.

Reduces redundancy and saves development time.

Improves program organization using hierarchical structures.

Supports the concept of polymorphism.

Disadvantages of Inheritance

Increases program complexity in deep inheritance hierarchies.

May introduce dependency between base and derived classes.

Improper use may lead to confusion in large programs.

Examples of Inheritance Use

Creating specialized classes from a general class (e.g., Vehicle → Car, Bike).

GUI frameworks (base window class extended into buttons, text boxes, etc.).

File handling, exception handling, and reusable libraries.

## Algorithm :

Start.

Define the base class with data members and member functions.

Define the derived class using syntax:

class Derived : access-specifier Base


The derived class can access the properties and functions of the base class (according to access specifier).

Create an object of the derived class.

Access base and derived class members using this object.

Stop.



## Conclusion:

Inheritance in C++ is a key OOP principle that allows one class to reuse the features of another, thereby reducing redundancy and promoting modularity. It supports extensibility, scalability, and polymorphism. While inheritance makes programs more organized and manageable, it should be used carefully to avoid complexity and tight coupling. Mastering inheritance is essential for understanding advanced OOP concepts such as polymorphism, virtual functions, and abstract classes.

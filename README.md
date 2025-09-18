# Inheritance-and-Error-Handling
## Aim:
To study and implement the concepts of Inheritance and Error Handling in C++.

## Theory:
### 🔹 Inheritance

Inheritance is one of the fundamental features of Object-Oriented Programming (OOP).

It allows a class (called the derived class) to acquire the properties and behaviors (data members and member functions) of another class (called the base class).

The main advantage is reusability: code written once in a base class can be reused in derived classes.

Inheritance also supports the concept of hierarchy and helps implement polymorphism.

Types of Inheritance in C++:

Single Inheritance – One base class and one derived class.

Multiple Inheritance – A derived class inherits from more than one base class.

Multilevel Inheritance – A class is derived from another derived class (grandparent → parent → child).

Hierarchical Inheritance – Multiple classes are derived from a single base class.

Hybrid Inheritance – A combination of more than one type of inheritance.

#### Advantages:

Promotes code reusability.

Provides a natural way to model real-world relationships.

Makes code easier to extend and maintain.

### 🔹 Error Handling

Errors are unexpected situations that may occur during the execution of a program (like division by zero, invalid input, file not found, etc.).

In C++, errors can be handled using the exception handling mechanism (try, catch, throw).

This ensures that instead of a program crashing on error, it can handle the error gracefully and continue execution.

Keywords used in Error Handling:

try → Defines a block of code to be tested for errors.

throw → Used to signal (raise) an exception when an error occurs.

catch → Defines a block of code to handle the exception.

#### Advantages:

Prevents program from abnormal termination.

Provides a structured way to handle runtime errors.

Increases the robustness and reliability of software.

## Algorithm:

Start the program.

For Inheritance:

Define a base class with data members and member functions.

Define a derived class that inherits from the base class.

Use inheritance (single, multiple, or multilevel) to demonstrate reusability.

Access base class members through derived class objects.

#### For Error Handling:

Identify operations that may generate runtime errors (e.g., division by zero, invalid input).

Place such operations inside a try block.

Use throw to raise an exception if an error occurs.

Handle the exception using a catch block.

Display the results of inheritance and error handling.

Stop the program.

## Conclusion:

From this experiment, we conclude that:

Inheritance allows a class to reuse the properties and functions of another class, supporting the concept of code reusability, extensibility, and hierarchy.

Error Handling using try, catch, and throw makes programs more reliable and prevents abnormal termination during runtime errors.

Both inheritance and error handling are powerful features of C++ that make programs robust, efficient, and maintainable.

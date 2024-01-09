Python - Inheritance
This project focuses on the concept of inheritance in object-oriented programming using Python. It covers various aspects of inheritance, including superclass, subclass, method overriding, multiple inheritance, and more.

Table of Contents
General
Requirements
Tasks
Usage
Contributing
License
General
Inheritance is a powerful feature of object-oriented programming that allows you to define a new class (subclass) based on an existing class (superclass or parent class). The subclass inherits the attributes and methods of the superclass, allowing code reuse and promoting code organization and modularity.

Python is a great programming language for implementing inheritance due to its flexibility and support for multiple inheritance. Understanding inheritance in Python is essential for building complex applications and designing object-oriented solutions.

In this project, we explore the following learning objectives:

Understanding why Python programming is awesome
Knowing the concepts of superclass, subclass, and inheritance hierarchy
Listing attributes and methods of a class or instance
Adding new attributes to instances
Defining a class with multiple base classes
Overriding methods or attributes inherited from the base class
Accessing attributes and methods inherited by subclasses
Understanding the purpose of inheritance in object-oriented programming
Using built-in functions like isinstance, issubclass, type, and super
Requirements
Python 3.8.5
pycodestyle 2.8.* (for code style enforcement)
Tasks
The project consists of several tasks, each focusing on a specific aspect of inheritance in Python. The tasks include:

Lookup: Implement a function to retrieve the attributes and methods of an object.
My list: Create a subclass of the built-in list class and add a method to print the list in sorted order.
Same class or inherit from: Write a function to check if an object is an instance of, or inherits from, a specified class.
Only sub class of: Implement a function to determine if an object is an instance of a class that directly or indirectly inherits from a specified class.
Geometry module: Create an empty class called BaseGeometry.
Improve Geometry: Extend the BaseGeometry class and add a method for calculating the area (raises an exception as it is not implemented).
Integer validator: Enhance the BaseGeometry class with a method to validate that a given value is an integer greater than 0.
Rectangle: Create a subclass of BaseGeometry called Rectangle and implement the area method.
Square: Create a subclass of Rectangle called Square and override the area method.
Full rectangle: Enhance the Rectangle class with width and height attributes and update the area method to calculate the area of a rectangle.
Full square: Enhance the Square class with a size attribute and update the area method to calculate the area of a square.
My integer: Create a subclass of int called MyInt and override the equality operator to invert its behavior.
Can I? Implement a function to determine if an object can be compared using the == operator.
Each task has its own Python script and test case file.

Usage
To run the project and execute the code for each task, follow these steps:

Clone the repository: git clone https://github.com/mugambi12/your-project.git
Navigate to the project directory: cd your-project
Run the desired task script: python task1.py, python task2.py, etc.
Check the output and verify the correctness of the implementation.
Refer to the specific task's test case file for additional examples and edge cases.
Modify the code and experiment with your own implementations.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. Feel free to fork the repository and create your own version too!

Fork the project (click the Fork button in the top right corner)
Clone the forked project to your local machine
Create a new branch for your feature or bug fix
Make the necessary modifications or additions
Commit your changes and push the branch
Submit a pull request to the original repository
License
This project is licensed under the MIT License. See the LICENSE file for details.

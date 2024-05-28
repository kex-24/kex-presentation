# Horse Ranch Simulator

### Deadline
Complete this assignment before the next class.

### Instructions
For guidance on how to do and submit this exercise, please refer to the assignments section of the course webpage.

### Preparation
- Study the section on "Object-Oriented Programming" to understand the basics of Java classes, objects, and methods.
- Refer to online resources or textbooks for additional information on getters and setters, constructor methods, and the `main` method in Java.

### Learning Goals
After completing this task, you should be comfortable with:
* Creating and using Java classes
* Handling instance variables
* Implementing constructors
* Writing getter and setter methods
* Understanding and using the `main` method in Java
* Grasping the concept of scope and variable shadowing

### Troubleshooting Guide
1. First, check if other students have faced similar issues by looking at the course's online Q&A forum.
2. If your problem is new, post your question on the forum. Make sure your question is specific and includes a clear description of the problem.
3. Consult your TA during the lab session for immediate assistance.

### Assignment

Imagine you're in the scenic countryside, tasked with managing a bustling horse ranch. Your job is to create a Java program that models the horses and their interactions at the ranch.

#### Horse.java
Start by creating a Java file called `Horse.java`. This file will host the `Horse` class, encapsulating all the necessary attributes and behaviors of a horse.

Each horse should have the following attributes (variables):
- `String` name
- `int` age
- `int` speed
- `double` health
- `boolean` trained

Inside the `Horse` class, populate it with the appropriate Java code sections to reflect the attributes above. Begin by simply declaring these variables within the class scope but outside of any methods.

#### Main Method and Object Creation
Create a `main` method in `Horse.java`, where you will construct and manipulate instances of the `Horse` class. Start by creating a horse named "Blaze" with placeholder values for its attributes directly in the `main` method.

#### Getters and Setters
To adhere to good encapsulation practices, modify the access control of your horse attributes to private. Then, implement getter and setter methods for each attribute. These methods will control the access to the horse's attributes, allowing you to read and modify their values safely.

#### Constructor
Introduce a constructor method to the `Horse` class that allows for setting all of the horse's attributes at the time of its creation. Utilize this constructor in the `main` method to streamline the creation of your horse objects.

#### Displaying Horse Information
Implement a method called `displayInfo()` in the `Horse` class. This method should print out all the horse's attributes in a friendly, readable format to the console.

#### Horse Interactions: Speed Competition
Now let's simulate a race! Create another method in the `Horse` class called `race` that accepts another `Horse` object as a parameter. The method should compare the `speed` attributes of the two horses, update their `health` based on the exertion of the race, and print out the winner. Implement logic to ensure that the race affects each horse's `health` appropriately.

#### Finalizing Your Ranch Simulator
Create two additional horse objects in your `main` method, assigning them different attribute values through the constructor. Test the `race` method by having them compete against each other.

#### Understanding Scope: Variable Shadowing
Review and comprehend the concept of variable shadowing within the context of class methods, particularly in constructors and setters. Understand how the `this` keyword can be used to distinguish between instance variables and method or constructor parameters.

### Checklist
- Created a `Horse` class with the specified attributes and access control.
- Implemented getter and setter methods for all attributes.
- Added a constructor to the `Horse` class for initializing new objects.
- Created a method to display a horse's information.
- Designed a method for simulating horse races and demonstrating interaction between horse objects.
- Explored the concept of variable shadowing and the use of the `this` keyword.

### Bugs and Errors

Report any inconsistencies or errors found in this exercise on the course's Q&A forum. Contributions to refining this assignment are appreciated and acknowledged in the course materials.
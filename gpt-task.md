# Horse Ranch Programming Task

**Deadline**: This assignment should be completed before the next exercise session.

**Instructions**: For guidelines on how to complete and submit the assignment, please refer to the assignments section of the course manual.

**Preparation**:
- Review Module 2: Looking Inside Classes from the course material.
- Access the course material either through the Canvas course or directly via the course webpage.

### Learning Objectives
- Designing and defining Java classes.
- Working with instance fields.
- Implementing constructors.
- Understanding getters and setters.
- Utilizing the `main` method effectively.
- Grasping the concept of scope and variable shadowing in Java.

### Assignment Overview

In this programming task, you're going to model a Horse Ranch in Java. You will define a Java class to represent horses at a ranch, detailing their characteristics and behaviors.

### Task Description

#### Task 1: Defining Your Horse Class

Start by creating a new Java file named `Horse.java` within the `src` directory. This file will contain your `Horse` class definition. 

1. Define the  `Horse` class with the following instance fields (but do not assign any values to them within the class):
    - `String` name
    - `int` age
    - `String` breed
    - `boolean` isTrained
    - `double` speed

2. In your `Horse` class, also include a `main` method for testing your code.

#### Task 2: Constructing Horses

Within the `main` method of the `Horse` class, create an instance of a Horse object. This object is constructed without any initial values.

#### Task 3: Utilizing Fields and Constructors

Turn the instance variables of your Horse class private to encapsulate the data. This will require using constructors, getters, and setters for manipulating these fields.

1. Provide a constructor for the Horse class that accepts arguments for each field and sets them accordingly.
2. Implement getters and setters for each field following Java naming conventions.

#### Task 4: Adding Horse Behaviors

Implement methods within the Horse class to simulate behaviors or actions a horse might have, such as `gallop()` or `neigh()`. For this task, implement a method called `gallop()` that prints the horse's speed to the console.

#### Task 5: Modeling Horse Interactions

Create a method to simulate horse interactions, for example; `race()`. The `race()` method should accept another Horse object as an argument and compare their speeds. Print out the faster horse to the console.

#### Task 6: Printing Horse Information

Add a method named `printInfo()` to your Horse class. This method should print all details of the horse (name, age, breed, trained status, and speed) to the console.

#### Task 7: Scope and Variable Shadowing

Prepare to discuss examples of variable shadowing and how the `this` keyword in Java can be used to differentiate between instance variables and parameters with the same name.

### Submission Checklist
- Implement the `Horse` class with the specified fields.
- Incorporate a constructor for initializing horse objects.
- Create getters and setters for each field in the Horse class.
- Define the `gallop()` and `race()` methods as described.
- Ensure the `printInfo()` method accurately displays the horse's attributes.
- Be ready to discuss scope and variable shadowing in Java.

### Help and Support

If you encounter any issues or have questions:
1. Consult the FAQ section on the course page.
2. If your question remains unanswered, open a new issue on the course help forum with a descriptive title.

Should you identify any inconsistencies or errors in this task, kindly report them through the course's help forum. Your feedback is valuable for improving future iterations of this task.

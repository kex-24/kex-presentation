# My Little Pony, Java Unleashed!

## Deadline
The assignment is due by the end of next week's exercise session.

## Instructions
Make sure you follow the assignment submission instructions detailed in the course documents. The instructions cover how to format and where to submit your assignment.

## Preparation
Read and work through all questions in the module on Object-Oriented Programming focusing on classes and objects. Do not hesitate to consult additional resources or ask TAs if you're having trouble with the concepts.

## Learning Goals
- Understand and implement Java classes.
- Work with instance variables.
- Utilize constructors for object instantiation.
- Implement getter and setter methods.
- Manipulate objects using methods.
- Comprehend the principle of encapsulation in Java.
- Understand object interaction within a program.

## Trouble?
If you encounter problems, check if someone has already posted a similar issue. If not, create a new issue with a descriptive title and explanation of your problem. Assistance is always available at the weekly lab sessions.

## Assignment

In the whimsical land of Equestria, there exist magical creatures known as Ponies. Your task is to model these Ponies in Java. Imagine the characteristics and abilities these mystical beings possess and bring them to life through your programming skills.

### Getting Started
Create a new Java file named `Pony.java` in your project's `src` directory. Begin by outlining your `Pony` class in this file.

For the initial step, let's dive right into creating our first Pony! Implement a main method within your `Pony` class. Now, declare the following variables within the main method and assign initial values to them:
- `String` name
- `int` energyLevel
- `int` magicPower
- `int` happiness
- `boolean` isFlying

Verify your code runs without errors before proceeding.

### Adding More Ponies
Next, let's introduce two more Ponies to our story. Similar to the first Pony, assign them unique attributes. This step highlights the repetitive and cumbersome aspect of manually creating each Pony with its own set of attributes.

### Transition to Classes and Objects
To overcome the limitations observed in manually managing each Pony, you'll now transition to using object-oriented principles. Define the instance variables (fields) related to a Pony outside the main method but within the class. These fields should not be instantiated with values yet.

Inside the main method, instantiate a new Pony object. Use this object to assign values directly to its fields via the dot operator. This approach streamlines the process of object creation and management.

### Encapsulating Pony Data
To enhance data protection and integrity, modify the access modifiers of your fields to `private`. Then, implement getter and setter methods for each field. This practice, known as encapsulation, ensures controlled access to the object's data.

### Constructors Are Magic
To make Pony creation even more magical, introduce a constructor to your Pony class. Constructors allow for the direct assignment of values to an object's fields upon creation. Implement a constructor that accepts all necessary attributes as parameters.

Create several Ponies using your constructor and verify that your objects are correctly instantiated.

### Displaying Pony Information
Instead of printing each Pony's attributes individually, implement a `printInfo()` method. This method should neatly print all relevant information about the Pony to the console.

### Pony Interactions
Ponies can interact! Implement a method called `performMagic()` where one Pony can perform magic on another. The effect of the magic can vary based on your creativity (e.g., increasing happiness, changing energy levels). Ensure your method reflects these changes and prints a summary of the action.

### Understanding Variable Shadowing
Variable shadowing can lead to confusion. Look into provided examples, understand the concept, and be prepared to discuss solutions.

## Checklist
- Create individual Ponies within the main method (optional step).
- Define class fields for the Pony class.
- Utilize getters and setters for manipulating Pony instances.
- Implement a constructor for efficient Pony instantiation.
- Develop a `printInfo()` method for easy information display.
- Implement a `performMagic()` method for Pony interactions.
- Investigate variable shadowing examples and understand how to address them.

## Found an Issue?
If you encounter inconsistencies or errors in the assignment, please open a new issue with a descriptive title and a summary of the problem. Contributions are appreciated and will be recognized in the acknowledgments section.
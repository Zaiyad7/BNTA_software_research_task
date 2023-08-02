# Software design methodologies

## 1. Coupling and Cohesion

Coupling is the degree of dependancy between the modules in a software system and measures how much one module relies on other modules. Low coupling shows that the modules are loosely interconnected making them more independant, while high coupling indicates stronger dependance between modules making the code harder to maintain and more difficult to change without affecting other parts of the program.

Cohesion refers to the amount in which the elements within a module are related to accomplish a single task. High-cohesion means that the elements within a module are closely related and work together towards a common purpose, whereas low cohesion shows that the elements in the module are loosely related or perform a bunch of unrelated tasks, which increases code complexity and makes the code harder to maintain.

## 2. Top down and Bottom up design

Top down design is where the problem is divided into smaller sub-problems and each of those sub-problems are broken down into smaller sub-problems and this continues untill the problems are simple enough to be solved easily. The design process starts from a high-level overview of the program and goes progressivley goes into the details.

Bottom up design is the opposite of top-down design and starts by making individual modules first and then gradually combines them to create higher level functionalities and eventually the complete program. Instead of starting with a high-level overview, bottom up design creates invdividual building blocks and then assembles them to form the entire system.

Top-down design best describes a function oriented design as it is a software design that emphasizes breaking down the problem into smaller functions and each function is responsible for completing a specific task. This makes it resemble top-down design as it involves breaking the system into smaller functions that can be developed and tested independantly.

## 3. Design methodology for a class diagram

A class diagram is most useful in object oriented design as class diagrams show the structure of a system, representing its classes, attributes, methods and the relationships between them. Object oriented design is about organising the system's components into objects and defining those objects behaviour via methods. The class diagram allows for the visualization of the different classes and their relationships within the program and helps the developer to understand the software's structure and the interactions between the classes.

## 4. Four pillars of Object Oriented Programming (OOP)

 Encapsulation: This is the bundling of data and methods that operate on that data within a single object and hides the internal implementation details from the outisde world.
 Abstraction: Abstraction simplifies the complex entities into the essential characteristics by defining the classes that act as blueprints for creating objects.
 Inheritance: Inheritrance allows a subclass to inherit properties and behaviours from a superclass, which allows the code to be re-used and supports a parent-child relationship.
 Polymorphism: Polymorphism enables the objects of different classes to act as objects of a common superclass via a unified interface, allowing for dynamic method binding and more flexibility in the code.

 ## 5. Strategy pattern and implementation

 The strategy pattern is a behavioural design pattern that allows the user to choose from a family of algorithims at runtime. It defines a family of algorithims, encapsulates each one and makes them interchangable and this allows the user to switch between the different algorithims without modifying the existing code.

 In an object oriented system, the strategy pattern is usually implemented using interfaces or abstract classes for the strategies and classes for each algorithim. The user class holds a reference to the strategy interface and at runtime it can switch between the different strategies by setting the appropriate strategy instance.

 In a functional system the strategy pattern can be implemented using higher-order functions or lambda expressions. Rather then creating separate classes for each strategy, the strategies are defined as functions and the user can select the desired strategy by passing the desired function at runtime.

 ## 6. Designing a online payment system

 I would suggest the object oriented design (OOD) methodology. Object oriented design alllows for code reusability which lets us develop common components that can be reused across different sectors without requiring significant changes in the code. The encapsulation features of OOP also makes it eaiser to hide the implementation details of stuff like payment related methods within classes and alllows for the protection of sensitive information like credit-card details.

 Abstraction also helps in creating high level models that focus on the essential features which allows for the creation of generic payment interfaces and classes that can be extended or specialized for specific sectors as needed. Inheritance also allows for the creation of a hierachy for payment related classes, the common functionalities can be defined in a base class and can be specified further for different sectors in derived classes, which helps manage the different payment scenarios.

 Polymorphism also allows you to treat the different payment methods through a common interface and alllows the payment system to accomodate stuff such as new payment methods without altering the existing code. OOD also promotes a structured approach to the code that allows the developer to create a better organised system, as the program grows and evolves this approach makes it easier to maintain and extend the codebase.

Object oriented design allows for a payment system that can be built to be adaptable and scalable and makes it easier to implement and maintain future changes to accomodate the changes in market demands for different industries.





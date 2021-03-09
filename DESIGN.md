# Design Concepts

## Separation of Concerns
Suggests that any complex problem can be more easily handled if it is subdivided into pieces that can each be solved and/or optimized independently.

## Modularity
Software is divided into separately named and addressable components, sometimes called modules, that are integrated to satisfy problem requirements.

## Functional Independence
Design software so that each module addresses a specific subset of requirements and has a simple interface when viewed from other parts of the program structure.

## Refinement
An application is developed by successively refining levels of procedural detail. A hierarchy is developed by decomposing a macroscopic statement of function (a procedural abstraction) in a stepwise fashion until programming language statements are reached

## Aspects
Is a representation of a crosscutting concern.

## Refactoring
Is the process of changing a software system in such a way that it does not alter the external behavior of the code design yet improves its internal structure.

# [OO Basics](https://www.indeed.com/career-advice/career-development/what-is-object-oriented-programming)

## Abstraction
The process of filtering the available information and arriving at a subset that is essential for an application.

## Encapsulation
Classes and modules should be specified and designed so that information (algorithms and data) contained within one is inaccessible to others that have no need for such information.

## Inheritance
Isolate common pieces of data and operations into a class and then create specialized classes based on that class.

## Polymorphism
Enable a number of different operations to have the same name. This in turn decouples objects from one another, making each more independent.

# OO Principles

- Encapsulate what varies.
- Favor composition over ihneritance.
- Program to interfaces, not implementations.
- Strive for loosely coupled designs between objects that interact.
- Depend on abstractions. Don't depend on concrete classes.
- Talk only to your fiends.
- Don't call us, we'll call you.
- A class should have only one reason to change.

# SOLID Principles

## [Single Responsability](https://www.javaguides.net/2018/02/single-responsibility-principle.html)
A class should have one and only one responsability.

## [Open/Closed](https://www.javaguides.net/2018/02/open-closed-principle.html)
A class should be open for extension but closed for modification.

## [Liskov Substitution](https://www.javaguides.net/2018/02/liskov-substitution-principle.html)
Derived classes should be substitutable for their base class.

## [Interface Segregation](https://www.javaguides.net/2018/02/interface-segregation-principle.html)
Clients should not be forced to depend on methods they don't use.

## [Dependency Inversion](https://www.javaguides.net/2018/02/dependency-inversion-principle.html)
High-level concrete classes should not be dependent on other low-level concrete classes. Instead, they should depend on abstract classes or interfaces.
# Design Concepts

## Separation of Concerns
Suggests that any complex problem can be more easily handled if it is subdivided into pieces that can each be solved and/or optimized independently.


## Modularity
Software is divided into separately named and addressable components, sometimes called modules, that are integrated to satisfy problem requirements.

## Functional Independence
Design software so that each module addresses a
specific subset of requirements and has a simple interface when viewed from other parts of the program structure.

## Refinement
An application is developed by successively refining levels of procedural detail. A hierarchy is developed by decomposing a macroscopic statement of function (a procedural abstraction) in a stepwise fashion until programming language statements are reached

## Aspects
Is a representation of a crosscutting concern.

## Refactoring
Is the process of changing a software system in such a way that it does not alter the external behavior of the code design yet improves its internal structure.

# OO Basics

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

## Single Responsability
A class should have one and only one responsability.

## Open/Closed
A class should be open for extension but closed for modification.

## Liskov Substitution
Derived classes should be substitutable for their base class.

## Interface Segregation
Clients should not be forced to depend on methods they don't use.

## Dependency Inversion
High-level concrete classes should not be dependent on other low-level concrete classes. Instead, they should depend on abstract classes or interfaces.

# OO Design Patterns (GoF)

## Strategy
Define a family of algorithms, encaupsulates each one, and make them interchangeable. Strategy lets the algorithms vary independently from the clients that use it.

## Observer
Define a one-to-many dependency between objects so that when one object change state, all its dependents are notified and updated automatically.

## Decorator
Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality.

## Factory Method
Define an interface for creating an object but let subclasses decide which class to instantiate, Factory Method lets a class defer instantiation to the subclasses.

## Abstract Factory
Provide an interface for creating families of related or dependent objects without specifying their concrete classes.

## Singleton
Ensure a class only has one instance and provide a global point of access to it.

## Command
Encapsulate a request as an object, thereby letting you parameterize clients with different request, queue or log requests, and support undoable operations.

## Adapter
Converts the interface of a class into another interface clients expect. Let classes work together that couldn't otherwise because of incompatible interfaces.

## Facade
Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that make the subsystem easier to use.

## Template method
Define the skeleton of an algorithm in a operation, deferring some steps to subclasses. Template Method let subclasses redefine certain steps of an algorithm without changing the algorithm's structure.

## Iterator
Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

## Composite
Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and composition of objects uniformly.

## State
Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.

## Proxy
Provide a surrogate or placeholder for another object to control access to it.
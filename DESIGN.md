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

## [Abstract Factory (Creational)](https://www.tutorialspoint.com/design_pattern/abstract_factory_pattern.htm)
Provide an interface for creating families of related or dependent objects without specifying their concrete classes.

## [Builder (Creational)](https://www.tutorialspoint.com/design_pattern/builder_pattern.htm)
Separate the construction of a complex object from its representation so that the same construction process can create different representations.

## [Factory Method (Creational)](https://www.tutorialspoint.com/design_pattern/factory_pattern.htm)
Define an interface for creating an object but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to the subclasses.

## [Prototype (Creational)](https://www.tutorialspoint.com/design_pattern/prototype_pattern.htm)
Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.

## [Singleton (Creational)](https://www.tutorialspoint.com/design_pattern/singleton_pattern.htm)
Ensure a class only has one instance, and provide a global point of access to it.

## [Adapter (Structural)](https://www.tutorialspoint.com/design_pattern/adapter_pattern.htm)
Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn't otherwise because of incompatible interfaces.

## [Bridge (Structural)](https://www.tutorialspoint.com/design_pattern/bridge_pattern.htm)
Decouple an abstraction from its implementation so that the two can vary independently.

## [Composite (Structural)](https://www.tutorialspoint.com/design_pattern/composite_pattern.htm)
Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.

## [Decorator (Structural)](https://www.tutorialspoint.com/design_pattern/decorator_pattern.htm)
Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality.

## [Facade (Structural)](https://www.tutorialspoint.com/design_pattern/facade_pattern.htm)
Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that makes the subsystem easier to use.

## [Flyweight (Structural)](https://www.tutorialspoint.com/design_pattern/flyweight_pattern.htm)
Use sharing to support large numbers of fine-grained objects efficiently.

## [Proxy (Structural)](https://www.tutorialspoint.com/design_pattern/proxy_pattern.htm)
Provide a surrogate or placeholder for another object to control access to it.

## [Chain of responsability (Behavioral)](https://www.tutorialspoint.com/design_pattern/chain_of_responsibility_pattern.htm)
Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.

## [Command (Behavioral)](https://www.tutorialspoint.com/design_pattern/command_pattern.htm)
Encapsulate a request as an object, there by letting you parameterize clients with different requests, queue or log requests, and support undoable operations.

## [Interpreter (Behavioral)](https://www.tutorialspoint.com/design_pattern/interpreter_pattern.htm)
Given a language, define a represention for its grammar along with an interpreter that uses the representation to interpret sentences in the language.

## [Iterator (Behavioral)](https://www.tutorialspoint.com/design_pattern/iterator_pattern.htm)
Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

## [Mediator (Behavioral)](https://www.tutorialspoint.com/design_pattern/mediator_pattern.htm)
Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.

## [Memento (Behavioral)](https://www.tutorialspoint.com/design_pattern/memento_pattern.htm)
Without violating encapsulation, capture and externalize an object's internal state so that the object can be restored to this state later.

## [Observer (Behavioral)](https://www.tutorialspoint.com/design_pattern/observer_pattern.htm)
Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.

## [State (Behavioral)](https://www.tutorialspoint.com/design_pattern/state_pattern.htm)
Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.

## [Strategy (Behavioral)](https://www.tutorialspoint.com/design_pattern/strategy_pattern.htm)
Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

## [Template Method (Behavioral)](https://www.tutorialspoint.com/design_pattern/template_pattern.htm)
Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.

## [Visitor (Behavioral)](https://www.tutorialspoint.com/design_pattern/visitor_pattern.htm)
Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.
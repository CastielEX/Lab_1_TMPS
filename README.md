# Lab_1_TMPS - Calculator App in Python

## by Agatiev Dumitru

## Task : Build an app that will follow SOLID Principles using an OOP programing language

## Theory : 
### S - Single Responsibility Principle: a class should have only one reason to change.

### O - Open/Closed Principle: entities should be open for extension but closed for modification.

### L - Liskov Substitution Principle: subtypes must be substitutable for their base types.

### I - Interface Segregation Principle: clients should not be forced to depend on interfaces they do not use.

### D - Dependency Inversion Principle: high-level modules should not depend on low-level modules. Both should depend on abstractions.

## Description :
For this task I decided to create a simple calculator app that will follow all those principles and will be easy to implement. For an OOP language I picked Python cause is a short codding language in comparasion with Java for ex. and relative easy to learn

### SRP: The Calculator class has a single responsibility of performing mathematical operations.
### OCP: The mathematical operations are implemented as separate classes that implement the same interface, which allows for easy extension.
### LSP: The mathematical operations are substitutable for each other, as they all implement the same interface and follow the same contract.
### ISP: The InputHandler and ResultDisplayer interfaces only expose the necessary methods for each operation to function correctly.
### DIP: The Calculator class depends on abstractions (Operation interface) rather than concrete implementations, which makes it more flexible and reusable.

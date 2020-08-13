
# SOLID Design Principles

I will use this repository to practice and document the knowledge about S.O.L.I.D. Object-Oriented Design Principles.
The source code is Java with examples of Good and Bad practices.

- Single Responsibility Principle
- Open/Closed Principle
- Liskov Substitution Principle
- Interface Segregation Principle
- Dependency Inversion Principle


## Table of Contents

* [Single Responsibility Principle](#single-responsibility-principle)
* [Open Closed Principle](#open-closed-principle)
* [Liskov Substitution Principle](#Liskov-Substitution-Principle)
* [Interface Segregation Principle](#interface-segregation-principle)
* [Dependency Inversion Principle](#dependency-inversion-principle)


## What is a good object-oriented design?

A good object-oriented design allows us to build software in a way that it can follow the evolution of the business in an agile and safe way. This means that the code must be maintainable.
Any code which is not maintainable and cannot adapt to changing requirements very easily is code just waiting to become old-fashioned.
One of the fundamental qualities of a software engineer is writing code that is maintainable.


## Single Responsibility Principle

"A class should have one, and only one, reason to change."
As well as cards in a deck cannot have two suits, nor have two numbers, a class should no have more than one responsibility.
The Principle of Single Responsibility (SRP) is linked to the concept of Cohesion.
A component with high cohesion is a component that has only a single responsibility, that has in its functions, only what it really should do.

Bad Example of Code:
```java
class Example {

}
```

In the example above, class Example has responsibilities that are not yours, such as... So, we say that this class is not cohesive, that is, it has too many responsibilities, and what is worse, responsibilities that are not yours.
This brings complexity to develop tests.
When working with the type of architecture above, there is a false impression that the system is being built in a practical and simple way, because there are few classes to maintain, but when they start to expand, it is that we see how the system became much more complex and difficult to maintain.

Good Example of Code:
```java
class Example {
    
}
```

### Ganhos ao aplicar S.R.P. a classes:

* Facilidade de manutenção e evolução do código
* Código limpo e de fácil entendimento
* Facilidade para desenvolvimento de testes
* Redução do acoplamento
* Complexidade reduzida
* Coesão das classes



## Open Closed Principle


## Liskov Substitution Principle


## Interface Segregation Principle


## Dependency Inversion Principle


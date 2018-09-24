# An introduction to S.O.L.I.D Principles using PHP

The term SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible and maintainable.

### S for Single Responsibility Principle(S.R.P)

A class should have one, and only one, reason to change.(A responsibility is a reason to change)  
- Things that change for the same reasons should be together.
- Things that change for different reasons should **not** be together.

Symptoms of S.R.P violation:
- The class has many instance variables.
- The class has many public methods.
- Each method of the class uses other instance variables
- Specific tasks are delegated to private methods
- Rigidity: In order to change something, changes in multiple places should be applied.
- Tight coupling: Classes depend tightly on other classes, this leads to fragility.
- Fragility: One change breaks something completely different.

### O for Open/closed principle

You should be able to extend a class’s behavior, without modifying it.

### L for Liskov substitution principle

Derived classes must be substitutable for their base classes.

### I for Interface segregation principle

Make fine-grained interfaces that are client specific

### D for Dependency inversion principle

High-level modules should not depend on low-level modules. Both should depend on abstractions.

---
title: Javascript(SOLID){
date: "2019-08-13T17:08:32.169Z"
description: Object Oriented Programming design principles};
---
###Object Oriented Programming design principles};

SOLID is an acronym for 5 important design principles when doing OOP. These 5 principles were introduced by Robert C. Martin (Uncle Bob), in his 2000 paper Design Principles and Design Patterns. The actual SOLID acronym was, however, identified later by Michael Feathers.

The intention of these principles is to make software designs more understandable, easier to maintain and easier to extend.   
As a budding software engineer, these 5 principles are essential to know!

##S - Single responsibility principle

>A class should have one, and only one, reason to change.

In programming, the single responsibility principle states that every module or class should have responsibility over a single part of the functionality provided by the software.

You may have heard the quote: "Do one thing and do it well".  
This refers to the single responsibility principle, or the colloquialised opposite, "Jack of all trades; master of none."

In Uncle Bob's Principles of Object Oriented Design, he defines a responsibility as a 'reason to change', and concludes that a class or module should have one, and only one, reason to be changed.

Put simply, each function should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the function.

##O - Open/closed principle

>You should be able to extend a class's behavior, without modifying it.

In programming, the open/closed principle states that software entities (classes, modules, functions, etc.) should be open for extensions, but closed for modification.

If you have a general understanding of OOP, you probably already know about polymorphism. We can make sure that our code is compliant with the open/closed principle by utilising inheritance and/or implementing interfaces that enable classes to polymorphically substitute for each other.

##L - Liskov substitution principle

>Derived classes must be substitutable for their base classes.

This one is probably the hardest one to wrap your head around when being introduced for the first time.

In programming, the Liskov substitution principle states that if S is a subtype of T, then objects of type T may be replaced (or substituted) with objects of type S.  
This can be formulated mathematically as:

- Let x be a property provable about objects x of type T.  
- Then y should be true for objects y of type S, where S is a subtype of T.

More generally, it states that objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.

##I - Interface segregation principle

>Make fine grained interfaces that are client specific.

This principle is fairly easy to comprehend. In fact, if you're used to using interfaces, chances are that you're already applying this principle.

In programming, the interface segregation principle states that no client should be forced to depend on methods it does not use.

Put more simply, do not add additional functionality to an existing interface by adding new methods. Instead, create a new interface and let your class implement multiple interfaces if needed.

##D - Dependency inversion principle

>Depend on abstractions, not on concretions.

Finally, we got to the D, the last of the 5 principles. In programming, the dependency inversion principle is a way to decouple software modules. This principle states that:

- High-level modules should not depend on low-level modules. Both should depend on abstractions.
- Abstractions should not depend on details. Details should depend on abstractions.

To comply with this principle, we need to use a design pattern known as a dependency inversion pattern, most often solved by using dependency injection. Dependency injection is a huge topic and can be as complicated or simple as one might see the need for.

Typically, dependency injection is used simply by 'injecting' any dependencies of a class through the class' constructor as an input parameter.

Essentially, one should depend upon abstractions, not on concretions.

##Conclusion

By following these 5 SOLID principles, we all get to benefit from a reusable, maintainable, scalable and easy testable codebase; making them essential principles used by professional software engineers all around the globe.
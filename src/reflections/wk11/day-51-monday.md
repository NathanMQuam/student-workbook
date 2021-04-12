# Day 51

Nathan Quam

---

[Afternoon Challenge](link.com)

---
---

## Daily Journal

Read Foundations of C# > C# Inheritance and answer the following questions

1. What does Inheritance accomplish for us in C#?
`
Inheritance is a key part of object-oriented programming, as it lets us create classes that inherit from or extend base classes. This allows us to write more general, abstract class definitions, and get more specific with the child classes.
`

2. How does Member inheritance work in C#? Does a class inherit all members of the base class?
`
When a child class inherits from a base class, it inherits most of the base class's members. A class *does not* inherit __all__ members of the base class, specifically constructors and finalizers/destructors.
`

3. How does accessibility affect inheritance?
`
Accessibility, or visibility, directly affects inheritance by controlling what has access to a base class's members. For example, a public member can be accessed by anything that has access to the class/instance, while a private member can only be accessed within the member's class. Protected members are *only* accessible by child classes, meaning the base class does not implement them. Internal members are "visible in derived classes located in the same assembly as the parent class."
`

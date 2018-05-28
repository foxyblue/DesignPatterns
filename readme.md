# Design Patterns

This repo is intended to be used as practice for implementing patterns of design as a means of study.

 - **For theory see:** Design Patterns: Elements of Reusable Object-Oriented Software.
 - **For examples see:** [faif/python-patterns](https://github.com/faif/python-patterns)

## Design Principles:

 - Program to an interface, not an implementation
 - Favour object composition over class inheritance.

## Creational Patterns

(Chapter 3, page. 77)

### Summary

Creational design patterns abstract the instantiation process. A class creational pattern uses inheritance to vary the class that's instantiated, whereas an object creational pattern will delegate instantiation to another object.
These shift emphasis away from hard-coding a fixed set of behaviours toward defining a smaller set of fundamental behaviours that can be composed into any number of more complex one. This means creating objects with particular behaviours requires more than simply instantiating a class.

There are two recurring themes in these patterns:
 - They all encapsulate knowledge about which concrete classes the system uses.
 - They hide how instances of these classes are created and put together.

All we know about the object is their interfaces as defined by abstract classes. Consequently they give you a lot of flexibility in _what_ gets created, _who_ creates it, _how_ it gets created, and _when_. They let you configure a system with "product" objects that vary widely in structure and functionality.

Sometimes creational patterns are competitors, at other times they are complementary.

### See following implementations:

 - [Abstract Factory](design_patterns/creational/abstract_factory.py)
 - [Builder](design_patterns/creational/builder.py)
 - [Factory Method](design_patterns/creational/factory_method.py)
 - [Prototype](design_patterns/creational/prototype.py)
 - [Singleton](design_patterns/creational/singleton.py)

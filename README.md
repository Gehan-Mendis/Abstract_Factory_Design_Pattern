# Abstract_Factory_Design_Pattern
The book Design Patterns: Elements of Reusable Object-Oriented Software states that an Abstract Factory “provides an interface for creating families of related or dependent objects without specifying their concrete classes”. In other words, this model allows us to create objects that follow a general pattern.That means Abstract Factory lets a class returns a factory of classes. So, this is the reason that Abstract Factory Pattern is one level higher than the Factory Pattern.

An example of the Abstract Factory design pattern in the JDK is the newInstance() of javax.xml.parsers.DocumentBuilderFactory class.

An Abstract Factory Pattern is also known as Kit.

# Advantage of Abstract Factory Pattern
Abstract Factory Pattern isolates the client code from concrete (implementation) classes.
It eases the exchanging of object families.
It promotes consistency among objects.

# Usage of Abstract Factory Pattern
When the system needs to be independent of how its object are created, composed, and represented.
When the family of related objects has to be used together, then this constraint needs to be enforced.
When you want to provide a library of objects that does not show implementations and only reveals interfaces.
When the system needs to be configured with one of a multiple family of objects.

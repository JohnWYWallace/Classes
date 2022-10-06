# Classes
This is a introductory to Swift classes.

Classes are a way of defining a blueprint, much like a structure. It is a way for us to plan out properties and methods. When we finally run the app we will era able to initialize the class into an actual object. When it comes to classes there are some core concepts you must be aware of like inheritance, superclass, subclass, override and calling a method from a super class (super.method()).
Something to note is that the name of the class must also be the name of the file. 
## Defining a class:
class MyClass {	}
Initializing a class:
MyClass()

# Subclass
A subclass is a child of the superclass, it has the same properties, and methods as the superclass. The subclass can now go on and create its own methods and properties.
## Defining a subclass:
class SubClass: SuperClass {	}


# Structs Vs. Classes
Structs aren’t able to inherit ate like a class. Another difference would be that in a class you would have to initialize it manually but in a struct you don’t have to do this. According to Apple they recommend you use a struct by default and later on if you think it should be a class then you can change it. https://developer.apple.com/documentation/swift/choosing-between-structures-and-classes

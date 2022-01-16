# #100DaysOfCode Log - Round 1 - Julia Placzkowska

The log of my #100DaysOfCode challenge. Started on [January 14, Friday, 2021].

## Log

### R1D1 
**Today's Progress:** Learning about Design Patterns from [this article](https://www.freecodecamp.org/news/the-basic-design-patterns-all-developers-need-to-know/).

**Notes:**
There are 3 types of design patterns:

#### 1.	Creational
 - *Creational pattern* refers to class-creation or object-creation.
- *The Singleton Design Pattern* is the basic example of creational type. It's objective is to create only one instance of a class and provide only one global access point to that object. There can be many different implementations of singleton design, such as *Eager Instantion*, *Lazy Instantion*, *Thread-safe Instantion*.

#### 2. Structural
- *Structural pattern* increases the functionality of the classes without disturbing its composition.
- *The Decorator Design Pattern* allows adding new functionality to an exsiting object without altering its structure by creating a *decorator class* which wraps the original class and adds new functionalities.


#### 3. Behavioral
- *Behavioral pattern* focuses on how classes and objects communicate with each other.
- *The Command Design Pattern* encapsulates in an object all the data required for performing a given action.


### R1D2
**Today's Progress:** Diving deeper into the creational design pattern theory based on [GoF Design Patterns](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8).

**Notes:** *The Creational Patterns* are used to make design more flexible rather than smaller. Flexible design lets us change particular classes easily.


*1. Abstract Factory*
Intent: Provide an interface for creating families of related or dependent objects without specifying their concrete classes.

*2. Builder*
Intent: Separate the construction of a complex object from its representation so that the same construction process can create different representations.

*3. Factory Method*
Intent: Define an interface for creating an object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.

*4. Prototype*
Intent: Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.

*5. Singleton*
Intent: Ensure a class only has one instance, and provide a global point of access to it.

### R1D3
**Today's Progress:** Learning more about the structural design patterns theory based on [GoF Design Patterns](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8).

**Notes:**
 *The Structural Patterns* can be divided into two groups:*structural **class** patterns* and *structural **object** patterns*.
- *Structural **class** patterns* use inheritance to compose interfaces or implementations.
- *Structural **object** patterns* describe ways to compose objects to realize new functionality.


**GoF Structural Design Patterns:**


*1. Composite*
Class hierarchy made up of two kinds of objects: *primitive* & *composite*. *The composite objects* can compose both *primitive* and other *composite objects* into complex structures.

*2. Proxy*
*A proxy object*, which can be used in many ways: 
- as a local representative for an object in a remote address space,
- as a representation of a large object that should be loaded on demand,
- as access protection to a sensitive object.

*3. Flyweight*
Defines a structure for sharing objects focused on space efficiency by creating lots of little objects. *Flyweight objects* has no context-dependent state, so that they can be shared freely. Any additional information is passed to the *flyweight objects* only when needed.

*4. Facade*
A single object - called *facade* - that represents an entire subsystem (set of objects). 

*5. Bridge*
An object's abstration separated from it's implementation.

*6. Decorator*
Adding responsibilities to objects *dinamically* by nesting one *decorator object* within another.

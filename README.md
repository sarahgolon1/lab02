# Lab 02 -- Chapter 01

## Define the followint terms:
* object-state or behavior (instance) of a class
* class-blueprint (code) that defines how to create an object
* instance-a specific realization of any object,
* method-a collection of statements, in a class, used to manipulate (mutators) or access (accessors) information from an object of that class (behaves like a function in mathematics),
* signature-name of the method and type of parameter. I.e. the following signature changes the size of the instance 'box' of class 'Box' and does not give an output: void changeSize(Box box),
* parameter-an input of a method I.e. 'box' is the parameter in the example above
* type-defines what values the parameter is allowed to be,
* state- a set of values describing an object,
* source code-collection of written commands that compiles to create an executable program.,
* return value- output of a method,
* compiler-transforms source code into computer readable language.

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 -int
* "hello" -string
* 101 -int
* -1 -int
* true -boolean
* "33" -string
* 3.1415 -double

## What would you have to do to add a new field, for example one called name, to a circle object?

You would have to add a parameter to the constructor.

## Write the header for a method named send that has one parameter of type String, and does not return a value.

public void send(String mag)


## Write the header for a method named average that has two parameters, both of type int, and returns an int value.

public int average(int num1, int num2)

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.

It is an object of class Book


## Can an object have several different classes? Discuss.

An object can have several different classes because a class can be a member of another class.  For example, if "car" is in class "Vehicle" and "Vehicle" is in class "Machine", then "car" is in both Vehicle and Machine classes
